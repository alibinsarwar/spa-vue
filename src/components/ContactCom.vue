<template>
    <div id="contact" class="contact">
         <div class="container">
            <div class="row">
               <div class="col-md-12">
                  <div class="titlepage">
                     <h2>Requst A call  for You</h2>
                  </div>
               </div>
            </div>
         </div>
         <div class="con_bg">
            <div class="container-fluid">
               <div class="row">
                  <div class="col-md-5">
                     <div id="request" class="main_form">
                        <div class="row">
                           <div class="col-md-12 ">
                              <input class="contactus" placeholder="Name" type="type" name="Name" v-model="name"> 
                           </div>
                           <div class="col-md-12">
                              <input class="contactus" placeholder="Email" type="type" name="Email" v-model="email"> 
                           </div>
                           <div class="col-md-12">
                              <input class="contactus" placeholder="Phone Number" type="type" name="Phone Number" v-model="number">                          
                           </div>
                           <div class="col-md-12">
                              <input class="contactusmess" placeholder="Message" type="type" Message="Name" v-model="msg">
                           </div>
                           <div class="col-md-12">
                              <button class="send_btn" v-on:click="getData()">Send</button>
                           </div>
                        </div>
                    </div>
                  </div>
                  <div class="col-md-7">
                     <div class="co_tru">
                        <figure><img src="images/truc4.png" alt="#"/></figure>
                     </div>
                  </div>
               </div>
            </div>
         </div>
      </div>
</template>
<script>
export default{
    name: 'ContactCom',
    data(){
        return{
            name: null,
            email : null,
            number: null,
            mgs: null
        }
    },
    methods:{
        getData(){
            console.log(this.name , this.email , this.number , this.msg );
        }
    }
}
</script>