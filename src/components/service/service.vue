<template>
    <div class="service_box" :class="color">
        <i><img :src="img" alt="#"/></i>
        <h4>{{ text }}</h4>
    </div>
</template>
<script>
export default{
    name: 'SingleService',
    props:{
        text: String,
        img: URL,
        color: String
    }
}
</script>