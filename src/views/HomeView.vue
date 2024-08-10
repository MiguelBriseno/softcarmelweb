<template>
  <!-- <main> -->
  <!-- Hero section -->
  <div class="relative">


    <div class="mx-auto max-w-7xl px-6 py-2 sm:py-32 lg:flex lg:items-center lg:gap-x-10 lg:px-8 lg:py-2">
      <!-- Fondo color azul -->
      <div class="absolute inset-x-0 top-1/2 -z-10 -translate-y-1/2 transform-gpu overflow-hidden opacity-30 blur-3xl"
        aria-hidden="true">
        <div class="ml-[max(50%,38rem)] aspect-[1313/771] w-[82.0625rem] bg-gradient-to-tr from-[#03FDC2] to-[#1E90FF]"
          style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)">
        </div>
      </div>
      <div
        class="absolute inset-x-0 top-0 -z-10 flex transform-gpu overflow-hidden pt-8 opacity-25 blur-3xl xl:justify-end"
        aria-hidden="true">
        <div
          class="ml-[-22rem] aspect-[1313/771] w-[82.0625rem] flex-none origin-top-right rotate-[30deg] bg-gradient-to-tr from-[#03FDC2] to-[#1E90FF] xl:ml-0 xl:mr-[calc(50%-12rem)]"
          style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)">
        </div>
      </div>
      <!-- termina fondo color azul -->


      <div class="mx-auto max-w-2xl lg:mx-0 lg:flex-auto">

        <div class="flex items-center gap-6 my-10" >
          <p class="flex items-center font-bold text-xs sm:text-md text-blue-500"> <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" class="w-10 h-10"
              viewBox="0 0 48 48">
              <path fill="#e64a19" d="M26,17h-8c-3.866,0-7-3.134-7-7v0c0-3.866,3.134-7,7-7h8V17z"></path>
              <path fill="#7c4dff" d="M25,31h-7c-3.866,0-7-3.134-7-7v0c0-3.866,3.134-7,7-7h7V31z"></path>
              <path fill="#66bb6a"
                d="M18,45L18,45c-3.866,0-7-3.134-7-7v0c0-3.866,3.134-7,7-7h7v7C25,41.866,21.866,45,18,45z"></path>
              <path fill="#ff7043" d="M32,17h-7V3h7c3.866,0,7,3.134,7,7v0C39,13.866,35.866,17,32,17z"></path>
              <circle cx="32" cy="24" r="7" fill="#29b6f6"></circle>
            </svg>Prototipo Gratis</p>
          <p class="flex items-center gap-2 text-green-600 font-bold text-xs sm:text-md"> <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"
              class="size-10 sm:size-6">
              <path fill-rule="evenodd"
                d="M12 6.75a5.25 5.25 0 0 1 6.775-5.025.75.75 0 0 1 .313 1.248l-3.32 3.319c.063.475.276.934.641 1.299.365.365.824.578 1.3.64l3.318-3.319a.75.75 0 0 1 1.248.313 5.25 5.25 0 0 1-5.472 6.756c-1.018-.086-1.87.1-2.309.634L7.344 21.3A3.298 3.298 0 1 1 2.7 16.657l8.684-7.151c.533-.44.72-1.291.634-2.309A5.342 5.342 0 0 1 12 6.75ZM4.117 19.125a.75.75 0 0 1 .75-.75h.008a.75.75 0 0 1 .75.75v.008a.75.75 0 0 1-.75.75h-.008a.75.75 0 0 1-.75-.75v-.008Z"
                clip-rule="evenodd" />
              <path
                d="m10.076 8.64-2.201-2.2V4.874a.75.75 0 0 0-.364-.643l-3.75-2.25a.75.75 0 0 0-.916.113l-.75.75a.75.75 0 0 0-.113.916l2.25 3.75a.75.75 0 0 0 .643.364h1.564l2.062 2.062 1.575-1.297Z" />
              <path fill-rule="evenodd"
                d="m12.556 17.329 4.183 4.182a3.375 3.375 0 0 0 4.773-4.773l-3.306-3.305a6.803 6.803 0 0 1-1.53.043c-.394-.034-.682-.006-.867.042a.589.589 0 0 0-.167.063l-3.086 3.748Zm3.414-1.36a.75.75 0 0 1 1.06 0l1.875 1.876a.75.75 0 1 1-1.06 1.06L15.97 17.03a.75.75 0 0 1 0-1.06Z"
                clip-rule="evenodd" />
            </svg>
            Soporte Gratuito</p>
          <p class="flex items-center gap-2 text-violet-500 font-bold text-xs sm:text-md">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="size-10 sm:size-6">
              <path fill-rule="evenodd"
                d="M12.516 2.17a.75.75 0 0 0-1.032 0 11.209 11.209 0 0 1-7.877 3.08.75.75 0 0 0-.722.515A12.74 12.74 0 0 0 2.25 9.75c0 5.942 4.064 10.933 9.563 12.348a.749.749 0 0 0 .374 0c5.499-1.415 9.563-6.406 9.563-12.348 0-1.39-.223-2.73-.635-3.985a.75.75 0 0 0-.722-.516l-.143.001c-2.996 0-5.717-1.17-7.734-3.08Zm3.094 8.016a.75.75 0 1 0-1.22-.872l-3.236 4.53L9.53 12.22a.75.75 0 0 0-1.06 1.06l2.25 2.25a.75.75 0 0 0 1.14-.094l3.75-5.25Z"
                clip-rule="evenodd" />
            </svg>

            Atencion 24 horas
          </p>
        </div>

        <div class="flex">
          <div
            class="relative flex items-center gap-x-4 rounded-full px-4 py-1 text-sm leading-6 text-gray-700 ring-1 ring-gray-900/10 hover:ring-gray-900/20">
            <span class="font-semibold text-teal-700">Contactanos</span>
            <span class="h-4 w-px bg-gray-900/10" aria-hidden="true" />
            <router-link to="/contact" class="flex font-semibold items-center gap-x-1">
              <span class="absolute inset-0" aria-hidden="true" />
              Crea tu Software
              <ChevronRightIcon class="-mr-2 h-5 w-5 text-gray-400" aria-hidden="true" />
            </router-link>
          </div>
        </div>
        <h2 class="mt-10 max-w-lg text-4xl font-semibold tracking-tight text-gray-900 sm:text-5xl"><span
            class="font-bold text-teal-600">Crea</span> tu propio <span class="font-bold text-teal-600">Software</span>
          y lleva la <span class="font-bold text-teal-600">Productividad</span> al siguiente <span
            class="font-bold text-teal-600">Nivel</span> </h2>
        <p class="mt-6 text-lg leading-8 text-gray-600">
         [Nombre Empresa], le ayudamos a gestionar sus sistemas de información con soluciones innovadoras, permitiéndole
          enfocarse en lo que realmente importa: hacer negocios.</p>
        <div class="mt-10 flex items-center gap-x-6">
          <RouterLink to="/contact"
            class="flex gap-2 items-center rounded-md bg-teal-500 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-teal-6  00 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="size-6">
              <path
                d="M12.75 12.75a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM7.5 15.75a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5ZM8.25 17.25a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM9.75 15.75a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5ZM10.5 17.25a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12 15.75a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5ZM12.75 17.25a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM14.25 15.75a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5ZM15 17.25a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM16.5 15.75a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5ZM15 12.75a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM16.5 13.5a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5Z" />
              <path fill-rule="evenodd"
                d="M6.75 2.25A.75.75 0 0 1 7.5 3v1.5h9V3A.75.75 0 0 1 18 3v1.5h.75a3 3 0 0 1 3 3v11.25a3 3 0 0 1-3 3H5.25a3 3 0 0 1-3-3V7.5a3 3 0 0 1 3-3H6V3a.75.75 0 0 1 .75-.75Zm13.5 9a1.5 1.5 0 0 0-1.5-1.5H5.25a1.5 1.5 0 0 0-1.5 1.5v7.5a1.5 1.5 0 0 0 1.5 1.5h13.5a1.5 1.5 0 0 0 1.5-1.5v-7.5Z"
                clip-rule="evenodd" />
            </svg>


            Agendar Sesion
          </RouterLink>
          <router-link to="/about" class="text-sm font-semibold leading-6 text-gray-900">Acerca nosostros <span
              aria-hidden="true">→</span></router-link>
        </div>
      </div>
      <div class="mt-16 sm:mt-24 lg:mt-0 lg:flex-shrink-0 lg:flex-grow">
        <svg viewBox="0 0 366 729" role="img" class="mx-auto w-[22.875rem] max-w-full drop-shadow-xl">
          <title>App screenshot</title>
          <defs>
            <clipPath id="2ade4387-9c63-4fc4-b754-10e687a0d332">
              <rect width="316" height="684" rx="36" />
            </clipPath>
          </defs>
          <path fill="#4B5563"
            d="M363.315 64.213C363.315 22.99 341.312 1 300.092 1H66.751C25.53 1 3.528 22.99 3.528 64.213v44.68l-.857.143A2 2 0 0 0 1 111.009v24.611a2 2 0 0 0 1.671 1.973l.95.158a2.26 2.26 0 0 1-.093.236v26.173c.212.1.398.296.541.643l-1.398.233A2 2 0 0 0 1 167.009v47.611a2 2 0 0 0 1.671 1.973l1.368.228c-.139.319-.314.533-.511.653v16.637c.221.104.414.313.56.689l-1.417.236A2 2 0 0 0 1 237.009v47.611a2 2 0 0 0 1.671 1.973l1.347.225c-.135.294-.302.493-.49.607v377.681c0 41.213 22 63.208 63.223 63.208h95.074c.947-.504 2.717-.843 4.745-.843l.141.001h.194l.086-.001 33.704.005c1.849.043 3.442.37 4.323.838h95.074c41.222 0 63.223-21.999 63.223-63.212v-394.63c-.259-.275-.48-.796-.63-1.47l-.011-.133 1.655-.276A2 2 0 0 0 366 266.62v-77.611a2 2 0 0 0-1.671-1.973l-1.712-.285c.148-.839.396-1.491.698-1.811V64.213Z" />
          <path fill="#343E4E"
            d="M16 59c0-23.748 19.252-43 43-43h246c23.748 0 43 19.252 43 43v615c0 23.196-18.804 42-42 42H58c-23.196 0-42-18.804-42-42V59Z" />
          <foreignObject width="316" height="684" transform="translate(24 24)"
            clip-path="url(#2ade4387-9c63-4fc4-b754-10e687a0d332)">
            <img src="@/assets/screenShotFirefly.png" alt="" />
          </foreignObject>
        </svg>
      </div>
    </div>
  </div>

  <!-- Logo cloud -->
  <div class="mx-auto max-w-7xl px-6 lg:px-8 lg:py-8">
    <div
      class="mx-auto grid max-w-lg grid-cols-4 items-center gap-x-8 gap-y-12 sm:max-w-xl sm:grid-cols-6 sm:gap-x-10 sm:gap-y-14 lg:mx-0 lg:max-w-none lg:grid-cols-5">
      <img class="col-span-2 max-h-20 w-full object-contain lg:col-span-1" src="@/assets/Actuar.png"
        alt="ActuarSustentable  " width="158" height="48" />
      <img class="col-span-2 max-h-20 w-full object-contain lg:col-span-1" src="@/assets/Lions.png"
        alt="Lion's Proteccion" width="158" height="48" />
      <img class="col-span-2 max-h-20 w-full object-contain lg:col-span-1" src="@/assets/Eletromex.png" alt="Electromex"
        width="158" height="48" />
      <img class="col-span-2 max-h-20 w-full object-contain sm:col-start-2 lg:col-span-1" src="@/assets/AgaveAzul.png"
        alt="SavvyCal" width="158" height="48" />
      <img class="col-span-2 col-start-2 max-h-20 w-full object-contain sm:col-start-auto lg:col-span-1"
        src="@/assets/Munich.png" alt="Statamic" width="158" height="48" />
    </div>
  </div>

  <!-- Feature section -->
  <div class="mx-auto  max-w-7xl mt-10 sm:px-6 lg:px-8">
    <div
      class="relative isolate overflow-hidden bg-gray-900 px-6 py-20 sm:rounded-3xl sm:px-10 sm:py-24 lg:py-24 xl:px-24">
      <div
        class="mx-auto grid max-w-2xl grid-cols-1 gap-x-8 gap-y-16 sm:gap-y-20 lg:mx-0 lg:max-w-none lg:grid-cols-2 lg:items-center lg:gap-y-0">
        <div class="lg:row-start-2 lg:max-w-md">
          <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl">Aumenta tu Productividad.<br />Con un
            software hecho a la medida.</h2>
          <p class="mt-6 text-lg leading-8 text-gray-300">En SOFTCARMEL, nos especializamos en las creacion de
            aplicaciones y paginas web personalizadas para empresas de todos los tamaños.
            Nuestro equipo de expertos combina creatividad y tecnologia avanzada para ofrecer soluciones innovadoras que
            impulsen tu negocio hacia el exito.

          </p>
        </div>
        <img src="@/assets/screenFull.png" alt="Product screenshot"
          class="relative -z-20 min-w-full max-w-xl rounded-xl shadow-xl ring-1 ring-white/10 lg:row-span-4 lg:w-[64rem] lg:max-w-none"
          width="2432" height="1442" />
        <div class="max-w-xl lg:row-start-3 lg:mt-10 lg:max-w-md lg:border-t lg:border-white/10 lg:pt-10">
          <dl class="max-w-xl space-y-8 text-base leading-7 text-gray-300 lg:max-w-none">
            <div v-for="feature in primaryFeatures" :key="feature.name" class="relative">
              <dt class="ml-9 inline-block font-semibold text-white">
                <component :is="feature.icon" class="absolute left-1 top-1 h-5 w-5 text-teal-6  00"
                  aria-hidden="true" />
                {{ feature.name }}
              </dt>
              {{ ' ' }}
              <dd class="inline">{{ feature.description }}</dd>
            </div>
          </dl>
        </div>
      </div>
      <div
        class="pointer-events-none absolute left-12 top-1/2 -z-10 -translate-y-1/2 transform-gpu blur-3xl lg:bottom-[-12rem] lg:top-auto lg:translate-y-0 lg:transform-gpu"
        aria-hidden="true">
        <div class="aspect-[1155/678] w-[72.1875rem] bg-gradient-to-tr from-[#03FDC2] to-[#025E47] opacity-25"
          style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)" />
      </div>

    </div>
  </div>

  <!-- Feature section -->
  <div class="mx-auto mt-10 max-w-7xl px-6  lg:px-8">
    <div class="mx-auto max-w-2xl lg:text-center">
      <h2 class="text-base font-semibold leading-7 text-teal-600">SOFTCARMEL</h2>
      <p class="mt-2 text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Digitaliza tu proceso.</p>
      <!-- <p class="mt-6 text-lg leading-8 text-gray-600"></p> -->
    </div>
    <div class="mx-auto mt-16 max-w-2xl sm:mt-20 lg:mt-24 lg:max-w-none">
      <dl class="grid max-w-xl grid-cols-1 gap-x-8 gap-y-16 lg:max-w-none lg:grid-cols-3">
        <div v-for="feature in secondaryFeatures" :key="feature.name" class="flex flex-col">
          <dt class="flex items-center gap-x-3 text-base font-semibold leading-7 text-gray-900">
            <component :is="feature.icon" class="h-5 w-5 flex-none text-teal-600" aria-hidden="true" />
            {{ feature.name }}
          </dt>
          <dd class="mt-4 flex flex-auto flex-col text-base leading-7 text-gray-600">
            <p class="flex-auto">{{ feature.description }}</p>
            <p class="mt-6">
              <a :href="feature.href" class="text-sm font-semibold leading-6 text-teal-600">Learn more <span
                  aria-hidden="true">→</span></a>
            </p>
          </dd>
        </div>
      </dl>
    </div>
  </div>



  <!-- Testimonials section -->
  <div class="relative isolate mt-20  ">
    <svg
      class="absolute inset-0 -z-10 hidden h-full w-full stroke-gray-200 [mask-image:radial-gradient(64rem_64rem_at_top,white,transparent)] sm:block"
      aria-hidden="true">
      <defs>
        <pattern id="55d3d46d-692e-45f2-becd-d8bdc9344f45" width="200" height="200" x="50%" y="0"
          patternUnits="userSpaceOnUse">
          <path d="M.5 200V.5H200" fill="none" />
        </pattern>
      </defs>
      <svg x="50%" y="0" class="overflow-visible fill-gray-50">
        <path d="M-200.5 0h201v201h-201Z M599.5 0h201v201h-201Z M399.5 400h201v201h-201Z M-400.5 600h201v201h-201Z"
          stroke-width="0" />
      </svg>
      <rect width="100%" height="100%" stroke-width="0" fill="url(#55d3d46d-692e-45f2-becd-d8bdc9344f45)" />
    </svg>
    <div class="relative">
      <div class="absolute inset-x-0 top-1/2 -z-10 -translate-y-1/2 transform-gpu overflow-hidden opacity-30 blur-3xl"
        aria-hidden="true">
        <div class="ml-[max(50%,38rem)] aspect-[1313/771] w-[82.0625rem] bg-gradient-to-tr from-[#03FDC2] to-[#1E90FF]"
          style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)">
        </div>
      </div>
      <div
        class="absolute inset-x-0 top-0 -z-10 flex transform-gpu overflow-hidden pt-8 opacity-25 blur-3xl xl:justify-end"
        aria-hidden="true">
        <div
          class="ml-[-22rem] aspect-[1313/771] w-[82.0625rem] flex-none origin-top-right rotate-[30deg] bg-gradient-to-tr from-[#03FDC2] to-[#1E90FF] xl:ml-0 xl:mr-[calc(50%-12rem)]"
          style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)">
        </div>
      </div>

      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <div class="mx-auto max-w-xl sm:text-center">
          <h2 class="text-lg font-semibold leading-8 tracking-tight text-teal-500">Testimoniales</h2>
          <p class="mt-2 text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Hemos colaborado con cientos de
            personas increibles</p>
        </div>
        <div
          class="mx-auto mt-16 grid max-w-2xl grid-cols-1 grid-rows-1 gap-8 text-sm leading-6 text-gray-900 sm:mt-20 sm:grid-cols-2 xl:mx-0 xl:max-w-none xl:grid-flow-col xl:grid-cols-4">
          <figure
            class="col-span-2 hidden sm:block sm:rounded-2xl sm:bg-white sm:shadow-lg sm:ring-1 sm:ring-gray-900/5 xl:col-start-2 xl:row-end-1">
            <blockquote class="p-12 text-xl font-semibold leading-8 tracking-tight text-gray-900">
              <p>{{ `“${featuredTestimonial.body}”` }}</p>
            </blockquote>
            <figcaption class="flex items-center gap-x-4 border-t border-gray-900/10 px-6 py-4">
              <img class="h-10 w-10 flex-none rounded-full bg-gray-50" :src="featuredTestimonial.author.imageUrl"
                alt="" />
              <div class="flex-auto">
                <div class="font-semibold">{{ featuredTestimonial.author.name }}</div>
                <div class="text-gray-600">{{ `@${featuredTestimonial.author.handle}` }}</div>
              </div>
              <img class="h-10 w-auto flex-none" :src="featuredTestimonial.author.logoUrl" alt="" />
            </figcaption>
          </figure>
          <div v-for="(columnGroup, columnGroupIdx) in testimonials" :key="columnGroupIdx"
            class="space-y-8 xl:contents xl:space-y-0">
            <div v-for="(column, columnIdx) in columnGroup" :key="columnIdx"
              :class="[(columnGroupIdx === 0 && columnIdx === 0) || (columnGroupIdx === testimonials.length - 1 && columnIdx === columnGroup.length - 1) ? 'xl:row-span-2' : 'xl:row-start-1', 'space-y-8']">
              <figure v-for="testimonial in column" :key="testimonial.author.handle"
                class="rounded-2xl bg-white p-6 shadow-lg ring-1 ring-gray-900/5">
                <blockquote class="text-gray-900">
                  <p>{{ `“${testimonial.body}”` }}</p>
                </blockquote>
                <figcaption class="mt-6 flex items-center gap-x-4">
                  <img class="h-10 w-10 rounded-full bg-gray-50" :src="testimonial.author.imageUrl" alt="" />
                  <div>
                    <div class="font-semibold">{{ testimonial.author.name }}</div>
                    <div class="text-gray-600">{{ `@${testimonial.author.handle}` }}</div>
                  </div>
                </figcaption>
              </figure>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- </main> -->
</template>

<script>
import { CloudArrowUpIcon, ServerIcon, PresentationChartBarIcon } from '@heroicons/vue/20/solid'
// import { CloudArrowUpIcon, LockClosedIcon, ServerIcon,PresentationChartBarIcon } from '@heroicons/vue/20/solid'

export default {
  data() {
    return {
      correo: null,
      primaryFeatures: [
        {
          name: 'Organizacion de Datos.',
          description: 'Al crear una aplicación web personalizada, te ofrecemos una solución poderosa para organizar y acceder a tus datos de manera intuitiva y segura.',
          icon: CloudArrowUpIcon,
        },
        {
          name: 'Seguimiento de Proyectos y Tareas.',
          description: 'La gestión de proyectos y tareas se vuelve sencilla y eficiente con una aplicación web personalizada desarrollada por SOFTCARMEL',
          icon: PresentationChartBarIcon,
        },
        {
          name: 'Database backups.',
          description: 'Protege tu negocio con copias de seguridad automáticas de bases de datos, asegurando la recuperación rápida de datos y minimizando el tiempo de inactividad.',
          icon: ServerIcon,
        },
      ],
      secondaryFeatures: [
        {
          name: 'Organizacion de Datos',
          description:
            'Nuestras aplicaciones están diseñadas para centralizar toda tu información en una plataforma fácil de usar, permitiéndote gestionar tus operaciones con mayor precisión y eficiencia. Ya sea que necesites administrar inventarios, clientes, proyectos o cualquier otro tipo de datos, nuestras soluciones te brindan el control y la claridad que necesitas para tomar decisiones informadas y estratégicas.',
          href: '#',
          icon: CloudArrowUpIcon,
        },
        {
          name: 'Seguimiento de proyectos y tareas',
          description:
            'Puedes asignar tareas, establecer plazos, y seguir el progreso en tiempo real, asegurando que todos los miembros de tu equipo estén alineados y colaboren de manera efectiva.',
          href: '#',
          icon: PresentationChartBarIcon,
        },
        {
          name: 'Database backups',
          description:
            'Con nuestras herramientas avanzadas, puedes automatizar y programar copias de seguridad regulares para asegurarte de que tu información esté siempre protegida contra pérdidas accidentales, fallos del sistema o ataques cibernéticos.',
          href: '#',
          icon: ServerIcon,
        },
      ],
      featuredTestimonial: {
        body: ' Colaborar con SOFTCARMEL ha sido una experiencia transformadora para nuestro negocio. Necesitábamos un software personalizado para gestionar nuestras operaciones internas, y ellos entregaron una solución que superó nuestras expectativas. El nuevo sistema automatiza procesos críticos, reduce errores y ha mejorado significativamente nuestra eficiencia operativa.',
        author: {
          name: 'Francisco Garcia',
          handle: 'fco.garcia18',
          imageUrl:
            require("@/assets/paco.jpeg"),
          logoUrl: require("@/assets/azulAgave.png"),
        },
      },
      testimonials: [
        [
          [
            {
              body: 'Tras enfrentar varios intentos de ciberataques, recurrimos a SOFTCARMEL para mejorar nuestra seguridad informática. Su equipo realizó una auditoría exhaustiva y implementó medidas avanzadas para proteger nuestros datos.',
              author: {
                name: 'Leslie Gaona',
                handle: 'leslieGaona',
                imageUrl:
                  'https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80',
              },
            },
            // More testimonials...
          ],
          [
            {
              body: 'SOFTCARMEL implementó un sistema ERP que ha integrado todas nuestras funciones empresariales en una plataforma unificada. Desde la contabilidad hasta la gestión de inventarios, ahora tenemos una visión completa de nuestras operaciones. Este cambio ha mejorado la colaboración entre departamentos y ha optimizado nuestra cadena de suministro.',
              author: {
                name: 'Fabiola Rodas',
                handle: 'FabiRo',
                imageUrl:
                  require('@/assets/FabiolaRodas.png'),
              },
            },
            // More testimonials...
          ],
        ],
        [
          [
            {
              body: 'SoftCarmel desarrolló una aplicación web que ha sido crucial para la gestión de nuestros eventos. Desde el registro de participantes hasta la coordinación logística, todo se maneja sin problemas. Su capacidad para entender nuestras necesidades específicas y ofrecer soluciones efectivas ha sido impresionante..',
              author: {
                name: 'Erik Romero',
                handle: 'erikromero_18',
                imageUrl:
                  require("@/assets/ErickRomero.jpeg"),
              },
            },
            // More testimonials...
          ],
          [
            {
              body: 'SoftCarmel desarrolló una excelente aplicación web para nuestra aseguradora de vehículos. Ahora, nuestros clientes pueden gestionar pólizas, presentar reclamaciones y obtener cotizaciones fácilmente. Hemos mejorado la eficiencia interna y el servicio al cliente. SoftCarmel superó nuestras expectativas. ¡Muy recomendados!.',
              author: {
                name: 'Edgar Lopez',
                handle: 'EdgarLopez',
                imageUrl:
                  'https://images.unsplash.com/photo-1519345182560-3f2917c472ef?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80',
              },
            },
            // More testimonials...
          ],
        ],
      ]
    }
  }
}
</script>

<style></style>