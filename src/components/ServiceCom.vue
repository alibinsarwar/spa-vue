<template>
    <div id="service" class="service">
         <div class="container">
            <div class="row">
               <div class="col-md-10 offset-md-1">
                  <div class="titlepage">
                     <h2>Our Services</h2>
                     <p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, There </p>
                  </div>
               </div>
            </div>
            <div class="row">
               <div class="col-md-12">
                  <div class="service_main">
                    <SingleService text="FLY ANYWHERE" img="images/ser1.png" color="blu_colo"></SingleService>
                    <SingleService text="CARGO SERVICES" img="images/ser2.png" color="yelldark_colo"></SingleService>
                    <SingleService text="COURIER SERVICES" img="images/ser3.png" color="yell_colo"></SingleService>
                    <SingleService text="BOX STORAGE" img="images/ser4.png" color="yelldark_colo"></SingleService>
                    <SingleService text="100% safe" img="images/ser5.png" color="yell_colo"></SingleService>
                  </div>
               </div>
               <div class="col-md-12">
                  <a class="read_more" href="#">Read More</a>
               </div>
            </div>
         </div>
      </div>
</template>
<script>
import SingleService from './service/service.vue'
export default{
    name:'ServiceCom',
    components:{
        SingleService
    }

}
</script>