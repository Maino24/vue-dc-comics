<template>
  <div>
    <div class="containerHeader">
      <div>
        <img src="../assets/img/dc-logo.png" alt="">
      </div>
      <div>
        <nav>
          <ul>
            <li>CHARACTERS</li>
            <li>COMICS</li>
            <li>MOVIE</li>
            <li>TV</li>
            <li>GAMES</li>
            <li>COLLECTIBLES</li>
            <li>VIDEOS</li>
            <li>FANS</li>
            <li>NEWS</li>
            <li>SHOP</li>
          </ul>
        </nav>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderComp',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.containerHeader{
  width: 70%;
  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  justify-content: space-between;
}

img{
  width: 80%;
  
}

ul {
  list-style-type: none;
}

li {
  display: inline-block;
  margin: 0 5px;
  font-size: 0.8rem;
    padding: 5% 0;
}

li:hover{
  border-bottom: 10px solid rgba(2, 130, 249, 1);
  color: rgba(2, 130, 249, 1);
  transition-delay: 0s;
}

</style>
