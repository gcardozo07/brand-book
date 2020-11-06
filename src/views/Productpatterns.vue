<template>
  <div class="container">
    <div class="sidebar">
      <Menu />
    </div>
    <div class="content">
      <div class="row-all">
        <div class="content-col-1">
          <h2>Product Patterns</h2>
        </div>
      </div>
      <div class="row-all">
          <div class="products-pattern">
              <div class="product"><figure><img src="../img/p1.png" alt="" /></figure></div>
              <div class="product"><figure><img src="../img/p2.png" alt="" /></figure></div>
              <div class="product"><figure><img src="../img/p3.png" alt="" /></figure></div>
              <div class="product"><figure><img src="../img/p4.png" alt="" /></figure></div>
              <div class="product"><figure><img src="../img/p5.png" alt="" /></figure></div>
              <div class="product"><figure><img src="../img/p6.png" alt="" /></figure></div>
          </div>
      </div>
      <div class="btn-res">
            <a target="_blank" href="https://drive.google.com/drive/folders/120DWf4FbGC30FX8qPdFq95foh4iRZ9cg?usp=sharing"><img src="../img/arrow.png" alt=""> Go to Resource</a>
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