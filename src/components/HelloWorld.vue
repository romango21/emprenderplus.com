<template>
  <div class="hello">
    <h3>Installed CLI Plugins</h3>
    <lottie
      :options="defaultOptions"
      :height="220"
      :width="180"
      v-on:animCreated="handleAnimation"
    />
  </div>
</template>

<script>
// import Lottie from "vue-lottie";
import * as animationData from "@/assets/bruja.json";
export default {
  name: "HelloWorld",
  data() {
    return {
      defaultOptions: { animationData: animationData },
      animationSpeed: 1
    };
  },
  methods: {
    handleAnimation: function(anim) {
      this.anim = anim;
    },

    stop: function() {
      this.anim.stop();
    },

    play: function() {
      this.anim.play();
    },

    pause: function() {
      this.anim.pause();
    },

    onSpeedChange: function() {
      this.anim.setSpeed(this.animationSpeed);
    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
