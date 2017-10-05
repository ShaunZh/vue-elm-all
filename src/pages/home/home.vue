<template>
  <div id="home">
    <header id="header">
      <div class="header--default">
        <div class="map">
          <p class="map__addr"></p>
        </div>
        <div class="weather">
          <div class="weather__desp">
            <p class="weather__temp"></p>
            <p class="weather__state"></p>
          </div>
          <div class="weather__img">
            <img src="" alt="">
          </div>
        </div>
      </div>

      <div class="header--active">
        <div class="search">
          <p class="search__tip">
            搜索商家、商品名称
          </p>
        </div>
      </div>

      <div class="hot-search">
        <nav>
              <ul>
                  <li><a href="#">正新鸡排</a></li><!--
               --><li><a href="#">木瓜</a></li><!--
               --><li><a href="#">肉蟹煲</a></li><!--
               --><li><a href="#">花甲</a></li><!--
               --><li><a href="#">华莱士</a></li><!--
               --><li><a href="#">麻辣烫</a></li><!--
               --><li><a href="#">鸡肉</a></li>
              </ul>
          </nav>
      </div>
    </header><!-- /header -->
    <section>
      <div class="foodentry">
        <div class="foodentry__items foodentry__items--active" >
          <a href="javascript:">
            <div class="container">

            </div>
            <span class=title>
              美食
            </span>
          </a>
          <a href="javascript:">
            <div class="container">

            </div>
            <span class=title>
              甜品饮品
            </span>
          </a>
          <a href="javascript:">
            <div class="container">

            </div>
            <span class=title>
              商超便利
            </span>
          </a>
          <a href="javascript:">
            <div class="container">

            </div>
            <span class=title>
              预定早餐
            </span>
          </a>
          <a href="javascript:">
            <div class="container">

            </div>
            <span class=title>
              果蔬生鲜
            </span>
          </a>
          <a href="javascript:">
            <div class="container">

            </div>
            <span class=title>

            </span>
          </a>
          <a href="javascript:">
            <div class="container">

            </div>
            <span class=title>

            </span>
          </a>
          <a href="javascript:">
            <div class="container">

            </div>
            <span class=title>

            </span>
          </a>
        </div>
        <div class="foodentry__items">

        </div>
      </div>
      <div class="foodentry-indicators">
        <span class="foodentry-indicator foodentry-indicator--active"></span>
        <span class="foodentry-indicator"></span>
      </div>
    </section>
    <section>
      <section class="banner-container">
        <img src="" alt="">
      </section>
      <section class="main-recommend">
        <div class="main-recommend__item--limit">
          <h3>限量抢购</h3>
          <p class="desp">超值美味9.9元起</p>
          <p class="state"><span>9人</span>正在抢 &lg;</p>
          <img src="" alt="">
        </div>
        <div class="main-recommend__item--hot">
          <h3>热卖套餐</h3>
          <p class="desp">销量最高，好评最多</p>
          <p class="state">TOP 100 &lg;</p>
          <img src="" alt="">
        </div>
      </section>
      <section class="sub-recommend">
        <div class="recommend-items">
          <div class="recommend-item">
            <h3>天天特价</h3>
            <p class="desp">低至1折</p>
            <img src="" alt="">
          </div>

          <div class="recommend-item">
            <h3>天天特价</h3>
            <p class="desp">低至1折</p>
            <img src="" alt="">
          </div>

          <div class="recommend-item">
            <h3>天天特价</h3>
            <p class="desp">低至1折</p>
            <img src="" alt="">
          </div>

        </div>
      </section>
    </section>
    <section class="recommend-shop">

    </section>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">

</style>