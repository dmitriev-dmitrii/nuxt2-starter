<template>
  <div id="__layout-defalut">
    <The-Header />
    <main >
      <nuxt />
    </main>
    <The-Footer />
  </div>
</template>

<script>
import TheHeader from '@/components/TheHeader';
import TheFooter from '@/components/TheFooter';

export default {
components:{
  TheHeader,
  TheFooter,
}
};

</script>


<style>


</style>
