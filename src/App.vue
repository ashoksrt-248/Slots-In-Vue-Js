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
    <div class="app4">
      <Card><h2>Card 11</h2><img src="https://picsum.photos/seed/seed10/300/200" width="210" height="200" /></Card>
      <Card><h2>Card 12</h2><img src="https://picsum.photos/seed/seed9/300/200"  width="210" height="200"/></Card>
      <Card><h2>Card 13</h2><img src="https://picsum.photos/seed/seed8/300/200"  width="210" height="200"/></Card>
      <Card><h2>Card 14</h2><img src="https://picsum.photos/seed/seed7/300/200" alt="Static Random Image 2" width="210" height="200"></Card>
      <Card><h2>Card 15</h2><img src="https://picsum.photos/seed/seed6/300/200" alt="Static Random Image 1" width="210" height="200"></Card>
    </div>
    <div class="app5">
      <Card><h2>Card 16</h2><img src="https://picsum.photos/seed/seed11/300/200" width="210" height="200" /></Card>
      <Card><h2>Card 17</h2><img src="https://picsum.photos/seed/seed12/300/200"  width="210" height="200"/></Card>
      <Card><h2>Card 18</h2><img src="https://picsum.photos/seed/seed13/300/200"  width="210" height="200"/></Card>
      <Card><h2>Card 19</h2><img src="https://picsum.photos/seed/seed14/300/200" alt="Static Random Image 2" width="210" height="200"></Card>
      <Card><h2>Card 20</h2><img src="https://picsum.photos/seed/seed15/300/200" alt="Static Random Image 1" width="210" height="200"></Card>
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
  color: azure;
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
.app4 {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 10px;
  background-color:palegreen;
  display: flex;
}
.app5 {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 10px;
  display: flex;
  background-color: darkcyan;
  color: aliceblue;
}
.heading{
  background-color: antiquewhite;text-align: center;font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
</style>
