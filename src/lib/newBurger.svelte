<script>
  let clicked = false;
  const alterarClick = () => {
    clicked = !clicked;
  };
</script>

<section class="my-20 md:my-10 sm:py-20 bg-[#202020]">
  <div class="nuevaBurger min-h-[100vh] flex flex-col justify-center gap-5">
    <div
      class="title text-5xl text-center text-neutral-50 md:text-6xl max-w-2xl mx-auto py-6 md:py-0"
    >
      <h1>Llego el nuevo fichaje a nuestro menu...</h1>
    </div>
    <div class="burger relative overflow-hidden">
      <div
        class="burgerimg relative w-full h-full flex justify-center items-center max-w-xl mx-auto p-2 overflow-hidden"
      >
        <div class="crispy flex flex-col gap-6 overflow-hidden">
          <img
            src="/nuevaCrispy.jpg"
            alt="nuevaburger"
            class="max-w-md h-full w-full
              {clicked ? 'blur-0' : ' blur-sm'}
                
              {clicked
              ? 'opacity-100'
              : 'opacity-5'} transition-all object-cover rounded-3xl shadow-md
                
                {clicked ? 'scale-100' : 'scale-110'}
                overflow-hidden
                shadow-yellow-900"
          />
          <div
            class="crispy_title text-center text-5xl lg:text-7xl text-yellow-600 font-bold {clicked
              ? 'blur-0'
              : 'blur-sm'} transition-all py-5"
          >
            <h1 class="">NUEVA CRISPY BURGER</h1>
          </div>
        </div>
        <div class="button absolute">
          <button
            class="btn w-44 text-3xl md:text-4xl md:btn-wide {clicked
              ? 'opacity-0'
              : 'opacity-100'} transition-all"
            on:click={alterarClick}>QUIERO VERLA</button
          >
        </div>
      </div>
    </div>
  </div>
</section>
