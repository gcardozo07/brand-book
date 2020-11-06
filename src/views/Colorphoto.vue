<template>
  <div class="container">
    <div class="sidebar">
      <Menu />
    </div>
    <div class="content">
      <div class="row-all">
        <div class="content-col-1">
          <h2>Color in Photography</h2>
        </div>
        <div class="content-col-2">
          <p>
            Don’t forget that color should be conveyed in large part through
            photography. Here are a few examples of how we’ve edited photography
            to include colors from our palette. All color treatment should be
            natural and authentic.
          </p>
        </div>
      </div>
      <div class="row-all">
        <div class="colorphoto">
            <div class="colorphotoin"><figure><img src="../img/c1.png" alt=""></figure></div>
            <div class="colorphotoin"><figure><img src="../img/c2.png" alt=""></figure></div>
            <div class="colorphotoin"><figure><img src="../img/c3.png" alt=""></figure></div>
            <div class="colorphotoin"><figure><img src="../img/c4.png" alt=""></figure></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Menu from "../components/Menu";
export default {
  components: {
    Menu,
  },
};
</script>


<style lang="scss" scoped>
.content{
    padding: 3rem;
}

</style>