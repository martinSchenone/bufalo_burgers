<section id="burgers">
  <div class="burgers flex flex-col items-center justify-center mt-10">
    <div
      class="title text-5xl lg:text-8xl border-b border-black mb-10 text-center"
    >
      Las mas pedidas
    </div>
    <div class="max-w-[80rem] text-4xl sm:text-5xl md:text-6xl my-10 ">
      <div class="title text-center text-5xl md:text-7xl py-4 font-bold">
        <h1 class=" text-neutral-900">CHESSE BURGER</h1>
      </div>
      <div class="burgerCard shadow-2xl">
        <div class="img col-start-1 col-end-3 h-full">
          <img
            src="/cheese.jpg"
            alt="burguer"
            class="w-full h-full object-cover"
          />
        </div>
        <div
          class="textBurger col-start-3 col-end-5 text-center bg-[#101010] text-neutral-50"
        >
          <div
            class="texto flex flex-col items-center justify-center h-full bg-neutral-900 p-6"
          >
            <p>- Pan de papa</p>
            <p>- Carne Smasheada</p>
            <p>- Queso Cheddar X4</p>
            <p>- Condimento de la casa</p>
          </div>
        </div>
      </div>
    </div>

    <div class="max-w-[80rem] text-4xl sm:text-5xl md:text-6xl my-10">
      <div class="title text-center text-5xl md:text-7xl py-4 font-bold">
        <h1 class="text-neutral-900">Bacon Cheese</h1>
      </div>
      <div class="burgerCard shadow-2xl">
        <div
          class="textBurger col-start-1 col-end-3 text-center bg-[#101010] text-neutral-50"
        >
          <div
            class="texto flex flex-col items-center justify-center h-full bg-neutral-900 p-6"
          >
            <p>- Pan de papa</p>
            <p>- Carne Smasheada</p>
            <p>- Queso Cheddar X2</p>
            <p>- Bacon Cheese</p>
            <p>- Salsa mil islas</p>
          </div>
        </div>
        <div class="img col-start-3 col-end-5 h-full">
          <img
            src="/baconcheese.jpg"
            alt="burguer"
            class="w-full h-full object-cover"
          />
        </div>
      </div>
    </div>

    <div class="max-w-[80rem] text-4xl sm:text-5xl md:text-6xl my-10">
      <div class="title text-center text-5xl md:text-7xl py-4 font-bold">
        <h1 class="text-neutral-900">Cuarto de libra</h1>
      </div>
      <div class="burgerCard shadow-2xl">
        <div class="img col-start-1 col-end-3 h-full">
          <img
            src="/cuarto.jpg"
            alt="burguer"
            class="w-full h-full object-cover"
          />
        </div>
        <div
          class="textBurger col-start-3 col-end-5 text-center bg-[#101010] text-neutral-50"
        >
          <div
            class="texto flex flex-col items-center justify-center h-full bg-neutral-900 p-6"
          >
            <p>- Pan de papa</p>
            <p>- Carne Smasheada</p>
            <p>- Queso Cheddar X4</p>
            <p>- Salsa cuarto de libra</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<style>
  @media all and (min-width: 600px) {
    .burgerCard {
      display: grid;
      grid-template-columns: 1rem minmax(0, 40rem) minmax(0, 40rem) 1rem;
      grid-template-rows: 500px;
    }
  }
</style>
