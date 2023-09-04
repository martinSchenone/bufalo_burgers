<script>
    import { register } from "swiper/element/bundle";
  register();
  const spaceBetween = 15;
</script>
<section id="hero">
  
<div class="hero min-h-screen bg-inherit pt-10 md:pt-0">
    <div
      class="flex flex-col items-center justify-center w-full py-5 lg:flex-row-reverse gap-6 shadow bg-[#202020] text-neutral-50"
    >
      <div class="cont w-[75vw] max-w-xl">
        <swiper-container
          class="h-[50svh] md:h-[60vh] lg:h-[70vh] w-full"
          loop={true}
          autoplay={true}
          space-between={spaceBetween}
        >
          <swiper-slide class=""
            ><img
              src="/burger2.jpg"
              alt=""
              class="object-cover rounded h-full w-full"
            /></swiper-slide
          >
          <swiper-slide class=""
            ><img
              src="/burga2.jpg"
              alt=""
              class="object-cover rounded h-full w-full"
            /></swiper-slide
          >
          <swiper-slide class=""
            ><img
              src="/burga3.jpg"
              alt=""
              class="object-cover rounded h-full w-full"
            /></swiper-slide
          >
        </swiper-container>
      </div>
      <div class="max-w-lg flex flex-col items-center justify-center text-center ">
        <h1 class="text-6xl tracking-wider font-bold">
          Degusta las hamburguesas mas deseadas del pais
        </h1>
        <div class="text py-6 text-4xl">
          <p>encontra nuestros locales en:</p>
          <div class="cities flex justify-evenly font-normal py-3">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="w-6 h-6"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z"
              />
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z"
              />
            </svg>
            <p>Mercedes</p>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="w-6 h-6"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z"
              />
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z"
              />
            </svg>
  
            <p>Palermo</p>
          </div>
        </div>
        <button
          class="btn text-4xl font-light bg-[#9A3B3B] border-[#9A3B3B] text-neutral-50 hover:opacity-60 hover:bg-[#9A3B3B] hover:border-[#9A3B3B]"
        >
          <a href="https://app.pedidosbcn.com/tienda/bufalo-burgers" target="_blank"
            >REALIZA TU PEDIDO!</a
          >
        </button>
      </div>
    </div>
  </div>
</section>
  