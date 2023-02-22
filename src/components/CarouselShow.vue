<template>
    <div>
        <el-carousel :interval="4000" type="card" height="380px">
            <el-carousel-item v-for="item in 6" :key="item">
                <el-image :src="img[item]" fit="fill" height="100%"></el-image>
            </el-carousel-item>
        </el-carousel>
    </div>
</template>

<script>
export default {
    name:'CarouselShow',
    data() {
      return {
        img:[
          "http://162.14.99.162/@1/img/carousel_img/1.jpg",
          "http://162.14.99.162/@1/img/carousel_img/2.jpg",
          "http://162.14.99.162/@1/img/carousel_img/3.jpg",
          "http://162.14.99.162/@1/img/carousel_img/4.jpg",
          "http://162.14.99.162/@1/img/carousel_img/5.jpg",
          "http://162.14.99.162/@1/img/carousel_img/6.jpg",
          "http://162.14.99.162/@1/img/carousel_img/7.jpg"
        ]
      }
    },
}
</script>

<style scoped>
.el-carousel {
  width: 75%;
  margin: auto;
}
</style>