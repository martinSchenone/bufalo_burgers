<div
  class="nav_container w-full min-h-[120px] h-full flex justify-center items-center shadow-md max-h-[30vh]"
>
  <nav class="navbar">
    <ul class="text-5xl space-x-3 navbar-start lg:flex hidden">
      <li class="hover:border-b border-neutral-600">
        <a href="#hero">HOME</a>
      </li>
      <li class="hover:border-b border-neutral-600">
        <a href="#burgers">BURGERS</a>
      </li>
      <li class="hover:border-b border-neutral-600">
        <a href="#contact">CONTACT</a>
      </li>
    </ul>
    <div class="dropdown lg:hidden navbar-start z-10">
      <label tabindex="0" class="btn btn-ghost btn-circle">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-5 w-5"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          ><path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h16M4 18h7"
          /></svg
        >
      </label>
      <ul
        tabindex="0"
        class="menu menu-sm dropdown-content mt-3 z-[1] p-2 shadow bg-base-100 rounded-box w-52
        "
      >
        <li><a href="#home" class="text-2xl">HOME</a></li>
        <li><a href="#burgers" class="text-2xl">BURGERS</a></li>
        <li><a href="#contact" class="text-2xl">CONTACTO</a></li>
      </ul>
    </div>

    <div
      class="navbar-center w-[min(90%,120px)] h-full flex justify-center items-center"
    >
      <a href="/">
        <img
          src="/logo2.png"
          alt=""
          class="h-full object-cover mix-blend-darken"
        />
      </a>
    </div>

    <div
      class="bufalo text-3xl sm:text-4xl lg:text-7xl font-bold tracking-tighter navbar-end text-center px-1"
    >
      <h1>BUFALO BURGERS</h1>
    </div>
  </nav>
</div>
