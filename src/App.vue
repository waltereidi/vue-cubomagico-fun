<script >
export default {
  data() {
    return {
      showElement: true,
    }
  },
  methods: {
    change() {
      setTimeout(async () => {
        this.showElement = !this.showElement;
        this.change();
      }, 500)
    }
  },
  mounted() {
    this.change();
  }
}

</script>

<template>
  <div class="content">
    <div class="boxshadows">


    </div>
    <div class="gradient" v-if="showElement">
      <div class="grid">
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
      </div>
    </div>
    <div class="gradient" v-if="!showElement">
      <div class="grid">
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
        <div class="grid-item"
          :style="{ 'background-color': 'color(display-p3 ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ' ' + Math.random().toFixed(20) + ')' }">
        </div>
      </div>
    </div>

  </div>
</template>

<style scoped>
@import "./assets/main.scss";
</style>
