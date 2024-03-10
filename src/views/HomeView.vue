<script setup>
</script>

<template>
  <div>
    <div class="hero">
      <h1 class="tittle">The Progressive <br> JavaScript Framework</h1>
      <div class="description">An approachable, performant and versatile framework for building web user interfaces.</div>
      <div class="action">
        <button class="button-why">Why Vue</button>
        <button class="button-get">Get Started -></button>
        <button class="button-install">install</button>
      </div>
    </div>
    <div class="special-sponsor">
      <div class="text">Special Sponsor</div>
      <div class="sponsor">app write</div>
      <div class="text">Open-source backend cloud platform</div>
    </div>
    <div class="detail">
      <div class="approachable">
        <div class="tittle">Approachable</div>
        <div class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum odit atque labore, tempore natus nam accusamus officiis magni perferendis explicabo!</div>
      </div>
      <div class="performant">
        <div class="tittle">Performant</div>
        <div class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum odit atque labore, tempore natus nam accusamus officiis magni perferendis explicabo!</div>
      </div>
      <div class="versatile">
        <div class="tittle">Versatile</div>
        <div class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum odit atque labore, tempore natus nam accusamus officiis magni perferendis explicabo!</div>
      </div>
    </div>
    <div class="platinum-sponsor">
      <div class="text">Platinum Sponsors</div>
      <div class="items">
        <div class="item" v-for="item in 11"></div>
      </div>
    </div>
    <div class="gold-sponsor">
      <div class="text">Gold Sponsors</div>
      <div class="items">
        <div class="item" v-for="item in 32"></div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  .hero {
    width: 80vw;
    max-width: 960px;
    margin: auto;
    padding-bottom: 96px;
    /* padding-top: 96px; */
    text-align: center;
    .tittle {
      font-size: 76px;
      font-weight: 1000;
      background-image: linear-gradient(to bottom right, rgb(0, 255, 89), rgb(0, 81, 255));
	    background-clip: text;
	    -webkit-text-fill-color: transparent;
    }
    .description {
      font-size: 22px;
      color: #8b8b8b;
      margin: 24px;
    }
    .action {
      display: flex;
      gap: 18px;
      justify-content: center;
      flex-wrap: wrap;
    }
    button {
      font-size: 16px;
      padding: 8px;
      padding-left: 16px;
      padding-right: 16px;
      border-radius: 5px;
      border: none;
      white-space: nowrap;
    }
    .button-why {
      background: #42b883;
      color: #213547;
    } 
    .button-get , .button-install {
      background: #2f2f2f;
      color: #aac8e4;
      
    }
    .button-get:hover , .button-install:hover {
      background: #ffffff11;
    }

    .button-why:hover {
      background: #42b8839a;
    }
  }
  .special-sponsor {
    display: flex;
    flex-wrap: wrap;
    border-top: 1px solid #525252;
    border-bottom: 1px solid #525252;
    left: 0;
    gap: 24px;
    justify-content: center;
    align-content: center;
    padding: 12px;
    
    div {
      align-self: center;
    }
    
    .sponsor {
      font-size: 24px;
    }
  }
  .detail {
    max-width: 960px;
    width: 80vw;
    margin: auto;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    color: #848484;
    gap: 5rem;
    margin-bottom: 8rem;

    .tittle {
      margin-top: 3rem;
      font-size: 20px;
      color: white;
      margin-bottom: 1rem;
    }
  }
  .platinum-sponsor{
    max-width: 960px;
    width: 80vw;
    margin: auto;
    .text {
      font-size: 20px;
      margin-bottom: 1.5rem;
    }
    .items{
      display: grid;
      grid-template-columns: repeat( 3 , 1fr );
      gap: 5px;
      .item {
        width: 100%;
        height: 7rem;
        background: #2f2f2f;
        border-radius: 5px;
      }
      .item:hover {
        background: #afafaf;
      }
    }
  }
  .gold-sponsor {
    max-width: 960px;
    width: 80vw;
    margin: auto;
    margin-bottom: 3rem;
    .text {
      font-size: 20px;
      margin-bottom: 1.5rem;
      margin-top: 4rem;
    }
    .items {
      display: grid;
      grid-template-columns: repeat(4,1fr);
      gap: 5px;
      .item{
        width: 100%;
        height: 6rem;
        background: #2f2f2f;
        border-radius: 5px;
      }
      .item:hover{
        background: #afafaf;
      }
    }
  }
  @media (max-width: 480px) {
    .hero {
      .tittle {
        font-size: 46px;
      }
    }
    .detail {
      grid-template-columns: 1fr;
      gap: 0;
    }
    .platinum-sponsor{
      .items {
        grid-template-columns: repeat(2 , 1fr);
        .item {
          height: 5rem;
        }
      }
    }
    .gold-sponsor {
      .items {
        grid-template-columns: repeat(2,1fr);
        .item {
          height: 4rem;
        }
      }
    }
  }
</style>
