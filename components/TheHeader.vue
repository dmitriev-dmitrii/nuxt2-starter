
<template>
<header>

  <div >

    <NuxtLink  to="/" exact class=""  >
        main
    </NuxtLink>

    <nav>
      <ul class="">
        <li  >
          <NuxtLink to="/users" >
              users
          </NuxtLink>
        </li>
      </ul>
    </nav>
  </div>
</header>
</template>

<script>

export default {

data:  () =>{
    return {

    }
	},
}
</script>

<style >

.nuxt-link-active {
  color: #00DC82 ;
  font-weight: bold;
  border-bottom: 2px solid currentColor;
}

</style>
