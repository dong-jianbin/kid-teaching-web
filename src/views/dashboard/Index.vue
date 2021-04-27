<template>
  <div>
    <h1>欢迎使用{{brandName}}教学系统</h1>
      <iframe
        id="player"
        :src="url"
        frameborder="0"
        width="100%"
        height="550px"
        scrolling="auto">
      </iframe>
  </div>
</template>

<script>


  export default {
    name: "Analysis",
    components: {

    },
    data() {
      return {
         brandName: window._CONFIG['brandName'],
         url: '/pixi/examples/17_treasureHunter.html'
      }
    },
    created() {
      // window.open('/pixi/examples/03_spriteFromImage.html')

    },
    methods: {

    }
  }
</script>