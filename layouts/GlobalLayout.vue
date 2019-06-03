<template>
  <div id="global-layout">
    <header style="background-color: #DDD">
      <router-link to="/">{{ $site.title }}</router-link>· <router-link to="/tag/">Tag</router-link>
    </header>
    <DefaultGlobalLayout/>
    <footer style="background-color: #DDD"><router-link to="https://github.com/ulivz">ULIVZ</router-link> · Powered by VuePress</footer>
  </div>
</template>

<script>
  import GlobalLayout from '@app/components/GlobalLayout.vue'
  
  export default {
    components: { DefaultGlobalLayout: GlobalLayout },
  }
</script>
