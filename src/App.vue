<template>
  <div id="app">
    <h1 class="heading"> Slots in VueJS</h1>
    <div id="app2">
      <Card><h2>Card 1</h2><img src="https://picsum.photos/200" width="210" height="200" /></Card>
      <Card><h2>Card 2</h2><img src="https://picsum.photos/300/200"  width="210" height="200"/></Card>
      <Card><h2>Card 3</h2><img src="https://picsum.photos/300/300"  width="210" height="200"/></Card>
      <Card><h2>Card 4</h2><img src="https://picsum.photos/seed/seed2/300/200" alt="Static Random Image 2" width="210" height="200"></Card>
      <Card><h2>Card 5</h2><img src="https://picsum.photos/seed/seed1/300/200" alt="Static Random Image 1" width="210" height="200"></Card>
    </div>
    <div class="app3">
      <Card><h2>Card 6</h2><img src="https://picsum.photos/300/200?blur=5" width="210" height="200" /></Card>
      <Card><h2>Card 7</h2><img src="https://picsum.photos/300/200?grayscale"  width="210" height="200"/></Card>
      <Card><h2>Card 8</h2><img src="https://picsum.photos/seed/seed3/300/200"  width="210" height="200"/></Card>
      <Card><h2>Card 9</h2><img src="https://picsum.photos/seed/seed4/300/200" alt="Static Random Image 2" width="210" height="200"></Card>
      <Card><h2>Card 10</h2><img src="https://picsum.photos/seed/seed5/300/200" alt="Static Random Image 1" width="210" height="200"></Card>
    </div>
  </div>
</template>

<script>
import Card from './components/Card.vue'
export default {
  name: 'App',
  components:{
    Card
  }
}
</script>

<style>
#app2 {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 10px;
  background-color: silver;
  display: flex;
}
.app3 {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 10px;
  background-color:sandybrown;
  display: flex;
}
.heading{
  background-color: antiquewhite;text-align: center;font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
</style>
