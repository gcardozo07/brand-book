<template>
  <div class="container">
    <div class="sidebar">
      <Menu />
    </div>
    <div class="content">
      <div class="row-all">
        <div class="content-col-1">
          <h2>Brand Patterns</h2>
          <p>
            We have developed an entire family of patterns to represent various
            tenets and offerings we provide.
            <br /><br />
            Our extended family of patterns ensures versatility and freshness
            within our design system.
          </p>
          <figure>
              <img class="image-b" src="../img/patt-brand-2.png" alt="" />
          </figure>
        </div>
        <div class="content-col-2">
          <img class="image-c" src="../img/patt-brand.png" alt="" />
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