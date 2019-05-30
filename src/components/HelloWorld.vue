<template>
  <div class="hello">
    <h1>
      <span>Welcome to </span> <span style="color: 	#3CB371"> jj-component </span> <span> on Vue! </span>
    </h1>
    <p> This is a demo Vue application that utilizes Team JayJay's web components </p>
    <h3>jj-input-number</h3>
    <br>
    <div class = "container2">
      <jj-input-number min=0 max=8 value=1 precision=2 step=0.5> </jj-input-number>
    </div>
    <br>
    <h3>jj-slider</h3>
    <div class="container" >
      <jj-slider id="jj" value=35 min=0 max=50 > </jj-slider>
    </div>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
  font-size: 50px;
}
h3 {
  margin: 40px 0 0;
}
h2 {
  margin: 50px 0 0;
}
.container{
  display: block;
  margin: 0 auto;
  width:40%;
}

.container2{
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 13%;
}

</style>
