<template>
  <div class="flex justify-between flex-wrap  w-screen p-8">
    <div class="p-8 m-8">
        <p>Hello! </p>
          <h1>I'm Amarachi Amaechi</h1>
            <span>Front-end Developer</span>
            <span>Technical Writer</span>
            <span>Community Expert</span>
            <div>
              <font-awesome-icon :icon="['fas', 'envelope']" />
              <a href="mailto:amarachiamaechi4@gmail.com" rel="noopener" target="_blank">amarachiamaechi4@gmail.com</a>
            </div>
            <div class="icons">
                <a href="https://github.com/amycruz97" rel="noopener" target="_blank"><font-awesome-icon :icon="['fab', 'github']" /></a>
                <a href="https://www.linkedin.com/in/amaechi-amarachi/" rel="noopener" target="_blank"><font-awesome-icon :icon="['fab', 'linkedin']" /></a>
                <a href="https://twitter.com/AmarachiAmaechi" rel="noopener" target="_blank"><font-awesome-icon :icon="['fab', 'twitter']" /></a>
                <a href="https://www.instagram.com/amycruz_97/" rel="noopener" target="_blank"><font-awesome-icon :icon="['fab', 'instagram']" /></a>


            </div>

    </div>
    <div>
        <img src="@/assets/images/pics.jpeg" alt="my logo" class="w-3/5 h-1/5" style="border-radius:50%">
    </div>


  </div>
</template>

<script>

export default {
  data(){
    return{
      
  }
}
}
</script>

<style scoped>


html,
body {
  height: 100%;
  width: 100%;
}

* {
  padding: 0;
  margin: 0;
}

</style>
