<template>
         <div id="content" class="main container p-3">
        <section>
          <h1>Contact</h1>
          <form>
            <div class="form-group">
              <label for="name">Name</label>
              <input 
              id="name"
              v-model="name"
              @input="handleInputChange"
              type="text" 
              autoComplete="off" 
              placeholder="Enter your name" 
              class="form-control" 
              required />

                <div>
                  <p class="error">{{ errorNameRequired }}</p>
                </div>
              
            </div>
            <div class="form-group">
              <label for="email">Email address</label> 
              <input 
              name="email"
              id="email"
              v-model="email"
              @input="handleInputChange"
              type="email" 
              autoComplete="off" 
              placeholder="Enter your email address" 
              class="form-control" 
              required
              aria-describedby="errorEmailRequired" />
                <div>
                  <p id="errorEmailRequired" role="alert" className="error">{{ errorEmailRequired }}</p>
                </div>

                <div>
                  <p id="errorEmailFormat" role="alert" className="error">{{ errorEmailFormat }}</p>
                </div>
              
            </div>
            <div class="form-group">
              <label for="message">Message</label>
              <textarea
              id="message" 
              name="message"
              v-model="message"
              @input="handleInputChange"
              class="form-control" 
              placeholder="Enter your message"></textarea>
               
               <div>
                  <p id="errorMessageRequired" role="alert" class="error">{{ errorMessageRequired }}</p>
               </div>
             
            </div>
            <div>
              <button class="btn" type="submit" @click="handleFormSubmit">Submit</button>
            </div>
          </form> 
        </section>
      </div>
</template>

<script>
export default {
    name: 'PageContact',
    data() {
      return {
        email: null,
        message: null,
        name: null,
      };
   },
    methods: {
        handleFormSubmit(){
           
        },
    },

}
</script>

<style>

</style>