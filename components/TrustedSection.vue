<template>
  <section class="trusted-section sd">
  <div class="price-table">
  <div class="price-card">
    <h3 class="price-card-header">Free</h3>
    <div class="price"><sup>MLN</sup>1.6<span>/Мес</span></div>
    <ul>
      <li><strong>Длительность:</strong><span style="font-size:24px;">10</span> сек</li>
      <li><strong>Количество показов в день</strong> <span style="font-size:24px;">:350-400</span></li>
      <li><strong><span style="font-size:24px;"> 3</span> месяц (сумм) скидка</strong><span style="font-size:24px;"> -5% 4 560 000 </span></li>
      <li><strong><span style="font-size:24px;">6</span> месяц (сумм) скидка </strong><span style="font-size:24px;">-10% 8 640 000</span></li>
      <li><strong><span style="font-size:24px;">12</span> месяц (сумм) скидка </strong><span style="font-size:24px;">-15% 16 320 000</span></li>
    </ul>
    <a href="#" class="order-btn">Заказать</a>
  </div>
  
  <div class="price-card">
    <h3 class="price-card-header">Bronze</h3>
    <div class="price"><sup>MLN</sup>2.5<span>/Мес</span></div>
    <ul>
      <li><strong>Длительность:</strong><span style="font-size:24px;">15</span> сек</li>
      <li><strong>Количество показов в день</strong> <span style="font-size:24px;">:350-400</span></li>
      <li><strong><span style="font-size:24px;"> 3</span> месяц (сумм) скидка</strong><span style="font-size:24px;"> -5% 7 12 5000 </span></li>
      <li><strong><span style="font-size:24px;">6</span> месяц (сумм) скидка </strong><span style="font-size:24px;">-10% 13 500 000</span></li>
      <li><strong><span style="font-size:24px;">12</span> месяц (сумм) скидка </strong><span style="font-size:24px;">-15% 25 500 000</span></li>
    </ul>
    <a href="#" class="order-btn">Заказать</a>
  </div>
  
  <div class="price-card">
    <h3 class="price-card-header">Gold</h3>
    <div class="price"><sup>MLN</sup>3.2<span>/Мес</span></div>
    <ul>
      <li><strong>Длительность:</strong><span style="font-size:24px;">20</span> сек</li>
      <li><strong>Количество показов в день</strong> <span style="font-size:24px;">:350-400</span></li>
      <li><strong><span style="font-size:24px;"> 3</span> месяц (сумм) скидка</strong><span style="font-size:24px;"> -5% 9 120 000 </span></li>
      <li><strong><span style="font-size:24px;">6</span> месяц (сумм) скидка </strong><span style="font-size:24px;">-10% 17 280 000</span></li>
      <li><strong><span style="font-size:24px;">12</span> месяц (сумм) скидка </strong><span style="font-size:24px;">-15% 32 640 000</span></li>
    </ul>
    <a href="#" class="order-btn">Заказать</a>
  </div>
   <div class="price-card">
    <h3 class="price-card-header">Platinum</h3>
    <div class="price"><sup>MLN</sup>4.0<span>/Мес</span></div>
    <ul>
      <li><strong>Длительность:</strong><span style="font-size:24px;">25</span> сек</li>
      <li><strong>Количество показов в день</strong> <span style="font-size:24px;">:350-400</span></li>
      <li><strong><span style="font-size:24px;"> 3</span> месяц (сумм) скидка</strong><span style="font-size:24px;"> -5% 11 400 000 </span></li>
      <li><strong><span style="font-size:24px;">6</span> месяц (сумм) скидка </strong><span style="font-size:24px;">-10% 21 600 000</span></li>
      <li><strong><span style="font-size:24px;">12</span> месяц (сумм) скидка </strong><span style="font-size:24px;">-15% 40 800 000</span></li>
    </ul>
    <a href="#" class="order-btn">Заказать</a>
  </div>
</div>
  </section>
</template>

<script>
    export default {
        name: "TrustedSection"
    }
</script>

<style scoped>

.price-table {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    width: min(1600px, 100%);
    margin: auto;
}

.price-card {
    
    flex: 1;
    max-width: 360px;
    background: #f1f1f1;
    margin: 20px 10px;
    text-align: center;
    overflow: hidden;
    cursor: pointer;
    transition: .2s linear;
    color: #2d2d2d;
}

.price-card-header {
    background: #0fbcf9;
    display: inline-block;
    padding: 12px 30px;
    color: #f1f1f1;
    font-size: 16px;
    border-radius: 0 0 20px 20px;
    text-transform: uppercase;
    font-weight: 600;
    transition: .4s linear;
}
.lii{
   font-weight: 600;
}

.price-card:hover .price-card-header{
    box-shadow: 0 0 0 50px #ff0e0e;

    
}


.price {
    font-size: 70px;
    margin: 40px 0;
    color: #0fbcf9;
    transition: .2s linear;
}

.price sup,
.price span {
    font-size: 22px;
    font-weight: 700;
}

.price-card:hover,
.price-card:hover .price {
    color: #ff0e0e;
}

.price-card li {
  z-index: 400;
    font-size: 16px;
    padding: 10px 0;
    text-transform: uppercase;
}
ul{
  z-index: 100;
}
.order-btn {
    display: inline-block; 
    margin-top: 80px;
    margin-bottom: 40px;
    border: 2px solid #0fbcf9;
    color: #0fbcf9;
    padding: 10px 25px;
    border-radius: 10px;
    text-transform: uppercase;
    font-weight: 500;
    transition: .3s linear;
}

.order-btn:hover {
    background: #ff0e0e;
    color: #f1f1f1;
    border: 2px solid #ff0e0e;
}

@media screen and (max-width:1100px) {
    .price-card {
        flex: 50%;
    }
}
</style>