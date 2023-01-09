<template>
    <div class="title">
        <div class="t1">{{subtitle}}</div>
        <div class="t2">{{title}}</div>
    </div>
</template>

<script>
export default {
    name: 'TitleText',
    props: ['title','subtitle']
}
</script>

<style scoped>
.title .t1{
  font-size: 1.5rem;
  /* font-size:24px; */
  color: #777777;
  letter-spacing: 5px;
}
.title .t2{
  font-size: 3.375rem;
  /* font-size: 54px; */
  font-weight: 600;
  color: #B94844;
  letter-spacing: 8px;
}

@media (max-width: 900px) {
  .title .t1{
    font-size: 1.2rem;
  }
  .title .t2{
    font-size: 3rem;
  }
}

@media (max-width: 400px) {
  .title .t1{
    font-size: 1rem;
  }
  .title .t2{
    font-size: 2.625rem;
  }
}
</style>