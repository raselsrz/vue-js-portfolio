
<template>
  <main>

    <!-- portfolio home page design  -->
    <section class="portfolio">

      <h2 class="section__title section__title--portfolio">My Portfolio</h2>

      <div class="portfolio__container">
        <div class="portfolio__item">
          <img src="https://rasel.somoy.xyz/uploads/1728734973.png" alt="portfolio item" />
          <h3>Portfolio Item</h3>
        </div>
        <div class="portfolio__item">
          <img src="https://rasel.somoy.xyz/uploads/1728618433.png" alt="portfolio item" />
          <h3>Portfolio Item</h3>
        </div>
        <div class="portfolio__item">
          <img src="https://rasel.somoy.xyz/public/uploads/1728152515.png" alt="portfolio item" />
          <h3>Portfolio Item</h3>
        </div>
        <div class="portfolio__item">
          <img src="https://rasel.somoy.xyz/uploads/1727520202.png" alt="portfolio item" />
          <h3>Portfolio Item</h3>
        </div>
        <div class="portfolio__item">
          <img src="https://rasel.somoy.xyz/public/uploads/1724101085.png" alt="portfolio item" />
          <h3>Portfolio Item</h3>
        </div>
        <div class="portfolio__item">
          <img src="https://rasel.somoy.xyz/public/uploads/1723590095.png" alt="portfolio item" />
          <h3>Portfolio Item</h3>
        </div>
      </div>
    </section>
    <!-- end portfolio home page design  -->



  </main>

  
</template>

<style scoped>
  .portfolio {
    padding: 50px 0;
    background-color: hsla(160, 100%, 37%, 1);
    border-radius: 10px;
    margin-top: 30px;
  }

  .portfolio__container {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
    gap: 20px;
    justify-content: center;
    align-items: center;
    padding: 0 20px;
  }

  .portfolio__item {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 20px !important;
    background-color:  hsla(160, 100%, 37%, 0.2);
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }

  .portfolio__item img {
    width: 100%;
    height: 130px;
    border-radius: 5px;
    transition: transform 0.3s;
  }

  .portfolio__item img:hover {
    transform: scale(1.1);
  }

  .portfolio__item h3 {
    margin-top: 10px;
    font-size: 1.2rem;
    font-weight: 500;
    color: #fff;
  }

  @media (min-width: 768px) {
    .portfolio__container {
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    }

    .portfolio__item {
      padding: 30px;
    }

    .portfolio__item h3 {
      font-size: 1.4rem;
    }
  }

  .section__title {
    font-size: 36px;
    font-weight: 700;
    margin-bottom: 30px;
    text-transform: uppercase;
    text-align: center;
    color: #fff;
  }


</style>
