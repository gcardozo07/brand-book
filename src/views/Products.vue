<template>
  <div class="container">
    <div class="sidebar">
      <Menu />
    </div>
    <div class="content">
    <div class="row-all">
        <div class="content-col-3">
            <h2>All Product Lockups</h2>
        </div>
      </div>
      <div class="row-all">
        <div class="content-col-3">
            <img src="../img/l1.png" alt="">
        </div>
        <div class="content-col-4">
            <img src="../img/l2.png" alt="">
        </div>
      </div>
      <div style="background: #f1f1f3" class="row-all">
        <div class="content-col-3">
            <img src="../img/l3.png" alt="">
        </div>
        <div class="content-col-4">
            <img src="../img/l4.png" alt="">
        </div>
      </div>
      <div class="row-all">
        <div class="content-col-3">
            <img src="../img/l5.png" alt="">
        </div>
        <div class="content-col-4">
            <img src="../img/l6.png" alt="">
        </div>
      </div>
      <div style="background: #f1f1f3" class="row-all">
        <div class="content-col-3">
            <img src="../img/l7.png" alt="">
        </div>
        <div class="content-col-4">
            <img src="../img/l8.png" alt="">
        </div>
      </div>
      <div class="row-all">
        <div class="content-col-3">
            <img src="../img/l9.png" alt="">
        </div>
        <div class="content-col-4">
            <img src="../img/l10.png" alt="">
        </div>
      </div>
      <div style="background: #f1f1f3" class="row-all">
        <div class="content-col-3">
            <img src="../img/l11.png" alt="">
        </div>
        <div class="content-col-4">
            <img src="../img/l12.png" alt="">
        </div>
      </div>
      <div class="btn-res">
            <a target="_blank" href="https://drive.google.com/drive/folders/1lL8QiZZePkSFCWslfP-vz1gHjMyBEo00?usp=sharing"><img src="../img/arrow.png" alt=""> Go to Resource</a>
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