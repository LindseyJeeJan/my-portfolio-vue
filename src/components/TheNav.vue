<template>
  <div>
        <a id='skip-nav' class='screenreader-text' href='#content'>
                Skip Navigation
        </a>
        <header>
            <div class="brand">Lindsey Lauria</div>
            <nav class="navbar navbar-dark navbar-expand-md">
                <ul class="nav nav-tabs w-100">
                <li class="nav-item">
                    <a
                    href="#about"
                    @click="handlePageChange('About')"
                    :class="currentPage === 'About' ? 'nav-link active' : 'nav-link'"
                    >
                    About Me
                    </a>
                </li>
                <li className="nav-item">
                    <a
                    href="#portfolio"
                    @click="handlePageChange('Portfolio')"
                    :class="currentPage === 'Portfolio' ? 'nav-link active' : 'nav-link'"
                    >
                    Portfolio
                    </a>
                </li>
                <li class="nav-item">
                    <a
                    href="#contact"
                    @click="handlePageChange('Contact')"
                    :class="currentPage === 'Contact' ? 'nav-link active' : 'nav-link'"
                    >
                    Contact
                    </a>
                </li>
                <li class="nav-item">
                    <a href="#resume"
                    @click="handlePageChange('Resume')"
                    :class="currentPage === 'Resume' ? 'nav-link active' : 'nav-link'"
                    >
                    Resume
                    </a>
                </li>
                </ul>
            </nav>
        </header>
    </div>
</template>

<script>
export default {
methods: {
    handlePageChange(page){
        console.log(page);
    }
}
}
</script>

<style scoped>

nav {
  flex: 1 0 0;
  font-weight: 300;
  width: 100%;
  flex-shrink: 0;
}

nav li {
    padding: 1%;
    justify-self: center;
    font-size: 1.1rem;
    font-weight: bold;
}

nav ul {
    justify-content: flex-end;
}
.navbar .nav-tabs .nav-link:hover{
    text-decoration: none;
}
</style>