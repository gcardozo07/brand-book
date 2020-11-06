<template>
  <div class="container">
    <div class="sidebar">
      <Menu />
    </div>
    <div class="content">
      <div class="row-all">
        <div class="content-col-1">
          <h2 data-animation="animated fadeInUp">Usage	Rules</h2>
          <p>
            Use this logo for non-marketing related
communications such as fi nancial documents,
building signage, letterheads, business cards,
etc. Maintaining clear space around the logo
ensures its readability:
<br><br>
As shown, full height of the letter ‘A’ is the
standard measurement for calculating the clear
space around the stand-alone logo.
Only the white or red logo may be used.
Download the Avaya logos in .jpeg, .eps, .gif
formats here
          </p>
        </div>
        <div class="content-col-2">
          <img src="../img/avaya-logo.png" alt="" />
        </div>
      </div>
      <div class="row-all">
        <figure>
          <img src="../img/logo-colors.png" alt="" />
        </figure>
      </div>
    </div>
  </div>
</template>

<script>
import Menu from "../components/Menu";
export default {
  components: {
    Menu
  },
};
</script>

<style lang="scss" scoped>
.content{
    padding: 3rem;
}

</style>