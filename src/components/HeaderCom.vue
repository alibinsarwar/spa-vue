<template>
    <div id="mySidepanel" class="sidepanel">
        <a href="javascript:void(0)" class="closebtn" v-on:click="closeNav()">×</a>
        <a href="index.html">Home </a>
        <a href="#about">About</a>
        <a href="#service">Services  </a>
        <a href="#vehicles">Our Vehicles</a>
        <a href="#testimonial">Testimonial</a>
        <a href="#contact">Contact</a>
    </div>
    <header>
         <!-- header inner -->
         <div class="header">
            <div class="container-fluid">
               <div class="row">
                  <div class="col-md-4 col-sm-4">
                     <div class="logo">
                        <a href="index.html"><img src="images/logo.png" alt="#" /></a>
                     </div>
                  </div>
                  <div class="col-md-8 col-sm-8">
                     <div class="right_bottun">
                        <ul class="conat_info d_none ">
                           <li><a href="#"><i class="fa fa-user" aria-hidden="true"></i></a></li>
                           <li><a href="#"><i class="fa fa-search" aria-hidden="true"></i></a></li>
                        </ul>
                        <button class="openbtn" v-on:click="openNav()"><img src="images/menu_icon.png" alt="#"/> </button> 
                     </div>
                  </div>
               </div>
            </div>
         </div>
      </header>
</template>
<script>
export default{
    name: 'HeaderCom',
    methods:{
        openNav() {
          document.getElementById("mySidepanel").style.width = "250px";
        },
        closeNav() {
          document.getElementById("mySidepanel").style.width = "0";
        }
    }
}
        
</script>