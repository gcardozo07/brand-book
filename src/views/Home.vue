<template>
  <div class="container">
    <div class="sidebar">
      <Menu />
    </div>
    <div class="content">
      <div class="home-in"></div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Menu from '../components/Menu'

export default {
  name: 'Home',
  components: {
    Menu
  }
}
</script>
<style lang="scss">
.container{
  display: inline-flex;
  .sidebar{
    flex-basis: 300px;
  }
  .content{
    flex-grow: 1;
    padding: 0;
    .home-in{
      width: 100%;
      height: 100vh;
      background-image: url('../img/back.jpg');
      background-size: cover;
    }
  }
}
</style>
