

<template>
  <section class="intro relative">           
    <Header></Header>
    <Banner></Banner>      
  </section>
  <brands>
  </brands>
  
  <section class="new-collection" id="new-collection">
      <main class="container">
          <h2 class="section-title">
              New Collection
          </h2>
          <div class="row">
              <div class="col-12 col-lg-5">
                  <div class="jacket">
                      <h3 class="jacket-title">
                          Men’s Jacket Collection
                      </h3>
                      <div class="jacket-picture-holder">
                          <img class="jacket-picture" src="./assets/image/2.png" alt="jacket" >
                      </div>
                      <div class="jacket-btn">
                          <a class="btn bg-dark" href="#" title="Discover" >Discover Now</a>
                      </div>
                  </div>
              </div>
              <div class="col-12 col-lg-7">
                  <div class="sunglass ">
                      <h3 class="sunglass-title">
                          Men’s Sunglasses<br> Collection
                      </h3>
                      <div class="sunglass-off">
                          40% OFF
                      </div>
                      <div class="sunglass-picture-holder">
                          <img class="sunglass-picture" src="./assets/image/3.png" alt="sunglass" >
                      </div>
                      <div class="sunglass-btn">
                          <a class="btn bg-dark" href="#" title="Discover" >Discover Now</a>
                      </div>
                  </div>
              </div>
          </div>
      </main>
  </section>
  <section class="best-sellers container-fluid" id="best-sellers">
      <div class="container">
          <h2 class="section-title">Best Sellers</h2>
          <div class="best-sellers-holder">
              <ul class="sellers-list row">
                  <li class="sellers-item col-auto col-lg-3 row">
                      <div class="sellers-image-holder col-12 g-0">
                          <img src="./assets/image/bag.jpg" alt="Backpack" class="seller-image img-fluid">
                          <a href="#" title="Add to Favorite" class="favorite-icon-link">
                                <img src="./assets/image/heart-logo.svg" alt="favorite" class="fav-icon-white">
                              <img src="./assets/image/filled-heart.svg" alt="favorite" class="fav-icon-black">
                              </a>    
                      </div>
                      <div class="sellers-details col-12 g-0">
                          <div class="sellers-name-price">
                              <div class="sellers-name">
                                  Fjallraven Backpack
                              </div>
                              <div class="sellers-price">
                                  $109.95
                              </div>
                          </div>
                          <div class="sellers-buying-link">
                              <a href="#" title="Go to Shop">
                                  <img src="./assets/image/shopping-cart.svg">
                              </a>
                          </div>
                      </div>
                  </li>
                  <li class="sellers-item col-auto col-lg-3 row">
                      <div class="sellers-image-holder col-12 g-0">
                          <img src="./assets/image/jacket.jpg" alt="Backpack" class="seller-image img-fluid">
                          <a href="#" title="Add to Favorite" class="favorite-icon-link">
                                <img src="./assets/image/heart-logo.svg" alt="favorite" class="fav-icon-white">
                              <img src="./assets/image/filled-heart.svg" alt="favorite" class="fav-icon-black">
                              </a>    
                      </div>
                      <div class="sellers-details col-12 g-0">
                          <div class="sellers-name-price">
                              <div class="sellers-name">
                                  Mens Cotton Jacket
                              </div>
                              <div class="sellers-price">
                                  $55.99
                              </div>
                          </div>
                          <div class="sellers-buying-link">
                              <a href="#" title="Go to Shop">
                                  <img src="./assets/image/shopping-cart.svg">
                              </a>
                          </div>
                      </div>
                  </li>
                  <li class="sellers-item col-auto col-lg-3 row">
                      <div class="sellers-image-holder col-12 g-0">
                          <img src="./assets/image/t-shirt.jpg" alt="slim-shirt" class="seller-image img-fluid">
                          <a href="#" title="Add to Favorite" class="favorite-icon-link">
                                <img src="./assets/image/heart-logo.svg" alt="favorite" class="fav-icon-white">
                              <img src="./assets/image/filled-heart.svg" alt="favorite" class="fav-icon-black">
                              </a>    
                      </div>
                      <div class="sellers-details col-12 g-0">
                          <div class="sellers-name-price">
                              <div class="sellers-name">
                                  Slim Fit T-Shirts
                              </div>
                              <div class="sellers-price">
                                  $22.3
                              </div>
                          </div>
                          <div class="sellers-buying-link">
                              <a href="#" title="Go to Shop">
                                  <img src="./assets/image/shopping-cart.svg">
                              </a>
                          </div>
                      </div>
                  </li>
                  <li class="sellers-item col-auto col-lg-3 row">
                      <div class="sellers-image-holder col-12 g-0">
                          <img src="./assets/image/slim-shirt.jpg" alt="slim-shirt" class="seller-image img-fluid">
                          <a href="#" title="Add to Favorite" class="favorite-icon-link">
                                <img src="./assets/image/heart-logo.svg" alt="favorite" class="fav-icon-white">
                              <img src="./assets/image/filled-heart.svg" alt="favorite" class="fav-icon-black">
                              </a> 
                          <div class="badge">-30%</div>    
                      </div>
                      <div class="sellers-details col-12 g-0">
                          <div class="sellers-name-price">
                              <div class="sellers-name">
                                  Mens Casual Slim Fit
                              </div>
                              <div class="sellers-price">
                                  <span class="off-price">$15.99</span>
                                  <span class="">$11.25</span>
                              </div>
                          </div>
                          <div class="sellers-buying-link">
                              <a href="#" title="Go to Shop">
                                  <img src="./assets/image/shopping-cart.svg">
                              </a>
                          </div>
                      </div>
                  </li>                        
              </ul>
          </div>
          <div class="sellers-btn d-none d-lg-block">
              <a href="#" title="load more products" class="btn bg-dark">Load More Products</a>
          </div>
      </div>
  </section>
  <section class="special-offer container-fluid" id="special-offer">
      <div class="container">
          <div class="timer-holder">
              <h4 class="timer-header">Sale ends soon</h4>
              <ul class="timer list-unstyled">
                  <li class="timer-item">
                      <div class="timer-number">3</div>
                      <div class="timer-unit">Days</div>
                  </li>
                  <li class="timer-item">
                      <div class="timer-number">23</div>
                      <div class="timer-unit">Hours</div>
                  </li>
                  <li class="timer-item">
                      <div class="timer-number">15</div>
                      <div class="timer-unit">Minutes</div>
                  </li>
                  <li class="timer-item">
                      <div class="timer-number">33</div>
                      <div class="timer-unit">Seconds</div>
                  </li>
              </ul>
          </div>
      </div>
      <div class="shoe-holder d-none d-md-block">
          <div class="shoe-off">70% OFF</div>
          <div class="shoe-picture">
              <img src="./assets/image/4.png" alt="shoe">
          </div>
          
      </div>
  </section>
</template>

<script >
import Header from '@/components/etalon/Header.vue'
import Banner from '@/components/etalon/Banner.vue'
import Brands from '@/components/etalon/Brands.vue'


export default{
  components: {
    Header,Banner,Brands,
  },
  data (){
    return{

    }
  },
  methods: {

  }
}
</script>

<style scoped>

</style>
