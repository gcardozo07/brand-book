<template>
  <div class="container">
    <div class="sidebar">
      <Menu />
    </div>
    <div class="content">
      <div class="row-all">
        <div class="content-col-1">
          <h2>Tagline</h2>
          <p>
            We help our customers create better experiences. And our experience
            helps us make sure those experiences matter.
            <br /><br />
            Our tagline helps convey this: Experiences That Matter. The tagline
            should be used whenever space and messaging allow for it.
          </p>
        </div>
        <div class="content-col-2">
          <img src="../img/avaya-logo-2.png" alt="" />
        </div>
      </div>
      <div class="row-all">
        <div class="content-col-1">
          <h2>Logo Crop</h2>
          <p>
            Our business is about helping other companies create experiences
            that matter. We always place the customer before ourselves as we are
            a portion—albeit an integral portion—of their experience.
            <br /><br />
            The cropped Avaya logo echoes this notion. We are a part of our
            customers’ stories, helping them create meaningful experiences;
            always supportive, never in the forefront.
          </p>
        </div>
        <div class="content-col-2">
          <img src="../img/crop.png" alt="" />
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