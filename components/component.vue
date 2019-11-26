<template>
  <div class="component-component">
    <div class="component-container">
      <a href="#" target="_blank" class="component-link">Link</a>
      <h1 class="component-heading1">Heading Level 1</h1>
      <p class="component-textblock">Paragraph</p>
    </div>
    <img src="/playground_assets/Screenshot 2019-11-25 at 18.02.22.png" class="component-image" />
    <img src="/playground_assets/Screenshot 2019-11-25 at 17.58.22.png" class="component-image1" />
    <img src="/playground_assets/IMG_20190123_134309-PANO.jpg" class="component-image2" />
    <img src="/playground_assets/IMG_20190123_135833.jpg" class="component-image3" />
    <img src="/playground_assets/facebook covers-03.jpg" class="component-image4" />
    <img src="/playground_assets/facebook covers-02.jpg" class="component-image5" />
  </div>
</template>

<script>
export default {
  name: 'AppComponent',
  props: {},
}
</script>

<style scoped>
.component-component {
  width: 900px;
  height: 671px;
  display: block;
  overflow: auto;
  font-size: 16px;
  font-family: Open Sans;
  background-color: #fff;
}
.component-container {
  width: 325px;
  height: 167px;
  background-color: rgba(20, 20, 20, 0.2);
}
.component-link {
  color: #000;
  cursor: pointer;
  text-decoration: underline;
}
.component-heading1 {
  font-size: 2em;
  margin-top: 0.67em;
  margin-bottom: 0.67em;
}
.component-textblock {
  margin-top: 1em;
  margin-bottom: 1em;
}
.component-image {
  width: 200px;
}
.component-image1 {
  width: 200px;
}
.component-image2 {
  width: 200px;
}
.component-image3 {
  width: 200px;
}
.component-image4 {
  width: 200px;
}
.component-image5 {
  width: 200px;
}
</style>
