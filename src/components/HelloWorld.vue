<template>
  <div class="container-fluid">
    <div class="card bg-light">
      <!-- <img class="card-img-overlay" src="https://banner2.kisspng.com/20180527/jvh/kisspng-minesweeper-classic-mines-minesweeper-for-androi-5b0a595546c4e9.9123787515274048852899.jpg"> -->
      <div class="card-header">Minesweeper!!</div>
      <div class="card-body align-self-center">
        <div class="d-flex justify-content-between">
          <div>
            <button class="text-center bg-dark text-white">bomb left:<br>00</button>
          </div>
          <div>
            <img class="btn iconbutton" src="https://icon-library.net/images/smile-icon/smile-icon-6.jpg">
          </div>
          <div>  
            <img class="btn iconbutton" src="https://www.pinclipart.com/picdir/big/65-654632_setting-icon-clipart-png-download.png" alt="">
          </div>
        </div>
        <div class="d-flex flex-nowrap field">
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
        </div>
        <div class="d-flex flex-nowrap field">
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
        </div>
        <div class="d-flex flex-nowrap field">
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
        </div>
        <div class="d-flex flex-nowrap field">
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
        </div>
        <div class="d-flex flex-nowrap field">
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
        </div>
        <div class="d-flex flex-nowrap field">
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
        </div>
        <div class="d-flex flex-nowrap field">
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
        </div>
        <div class="d-flex flex-nowrap field">
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
        </div>
        <div class="d-flex flex-nowrap field">
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
        </div>
        <div class="d-flex flex-nowrap field">
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
        </div>
        <div class="d-flex flex-nowrap field">
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
        </div>
        <div class="d-flex flex-nowrap field">
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
          <button>X</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@media screen and (max-width: 768){
  .field button {
    color: dimgrey;
    background-color: dimgray;
    scale: small;
  }  
}
.field button {
  color: dimgrey;
  background-color: dimgray;
  scale: small;
}
.iconbutton {
  width: 60px;
}
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
