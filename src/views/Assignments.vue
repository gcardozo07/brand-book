<template>
  <div class="container">
    <div class="sidebar">
      <Menu />
    </div>
    <div class="content">
        <div class="row-all">
            <div class="content-col-1">
        <h2>Color Assignments</h2>
      </div>
      <div class="content-col-2">
        <p>You’ll notice that our products utilize specific colors from our palette. Visual design of products
should use their primary colors prominently, supported by their secondary palette.</p>
      </div>
        </div>
        <div class="row-all">
            <div class="assignments">
                <div class="assignments-in">
                    <figure>
                       <img src="../img/a1.png" alt="">
                    </figure>
                </div>
                <div class="assignments-in">
                    <figure>
                       <img src="../img/a2.png" alt="">
                    </figure>
                </div>
                <div class="assignments-in">
                    <figure>
                       <img src="../img/a3.png" alt="">
                    </figure>
                </div>
                <div class="assignments-in">
                    <figure>
                       <img src="../img/a4.png" alt="">
                    </figure>
                </div>
                <div class="assignments-in">
                    <figure>
                       <img src="../img/a5.png" alt="">
                    </figure>
                </div>
                <div class="assignments-in">
                    <figure>
                       <img src="../img/a6.png" alt="">
                    </figure>
                </div>
                <div class="assignments-in-2">
                    <figure>
                       <img src="../img/a7.png" alt="">
                    </figure>
                </div>

            </div>
        </div>
    </div>
  </div>
</template>

<script>
import Menu from '../components/Menu'
export default {
    components:{
        Menu
    }

}
</script>

<style lang="scss" scoped>
.content{
    padding: 3rem;
}

</style>