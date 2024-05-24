<template>
  <section class="bg-white dark:bg-gray-900">
    <div class="grid max-w-screen-xl px-4 py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-16 lg:grid-cols-12">
        <div class="mr-auto place-self-center lg:col-span-7">
            <h1 class="max-w-2xl mb-4 text-4xl font-extrabold tracking-tight leading-none md:text-5xl xl:text-6xl dark:text-white">Sobre softcarmel</h1>
            <p class="max-w-2xl mb-6 font-light text-gray-500 lg:mb-8 md:text-lg lg:text-xl dark:text-gray-400">
              En Softcarmel ofrecemos una amplia gama de soluciones tecnológicas para distintas industrias y empresas de todos los tamaños. Creemos en las alianzas a 
              largo plazo y por ello nuestros servicios se diseñan con nuestros clientes en mente. Nos esforzamos para que nuestros clientes no tengan que preocuparse, 
              pues sus operaciones de tecnología de la información están en manos de profesionales.
            </p>
            <a href="https://wa.me/3322620459"  class="inline-flex items-center justify-center px-5 py-3 text-base font-medium text-center text-gray-900 border border-gray-300 rounded-lg hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 dark:text-white dark:border-gray-700 dark:hover:bg-gray-700 dark:focus:ring-gray-800">
              Agenda una reunión
            </a> 
        </div>
        <div class="hidden lg:mt-0 lg:col-span-5 lg:flex">
            <img src="../assets/hero.jpg" alt="Hero">
        </div>                
    </div>
  </section>

  <section>
    <div class="bg-white py-24 sm:py-32">
      <div class="mx-auto grid max-w-7xl gap-x-8 gap-y-20 px-6 lg:px-8 xl:grid-cols-3">
        <div class="max-w-2xl">
          <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Nuestro equipo</h2>
          <p class="mt-6 text-lg leading-8 text-gray-600">Somos un grupo de profesionales apasionados por el desarrollo de software, provenientes de un pueblo donde la honestidad, el trabajo duro y la responsabilidad son valores fundamentales. Nos comprometemos a ofrecer soluciones innovadoras y de alta calidad, ganándonos la confianza de nuestros clientes al entender sus necesidades y superar sus expectativas.</p>
        </div>
        <ul role="list" class="grid gap-x-8 gap-y-12 sm:grid-cols-2 sm:gap-y-16 xl:col-span-2">
          <li v-for="person in people" :key="person.name">
            <div class="flex items-center gap-x-6">
              <img class="h-16 w-16 rounded-full" :src="person.imageUrl" alt="" />
              <div>
                <h3 class="text-base font-semibold leading-7 tracking-tight text-gray-900">{{ person.name }}</h3>
                <p class="text-sm font-semibold leading-6 text-indigo-600">{{ person.role }}</p>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </section>

  <section>
    <div class="relative bg-gray-900">
      <div class="relative h-80 overflow-hidden bg-indigo-600 md:absolute md:left-0 md:h-full md:w-1/3 lg:w-1/2">
        <img class="h-full w-full object-cover" src="https://images.unsplash.com/photo-1525130413817-d45c1d127c42?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1920&q=60&blend=6366F1&sat=-100&blend-mode=multiply" alt="" />
        <svg viewBox="0 0 926 676" aria-hidden="true" class="absolute -bottom-24 left-24 w-[57.875rem] transform-gpu blur-[118px]">
          <path fill="url(#60c3c621-93e0-4a09-a0e6-4c228a0116d8)" fill-opacity=".4" d="m254.325 516.708-90.89 158.331L0 436.427l254.325 80.281 163.691-285.15c1.048 131.759 36.144 345.144 168.149 144.613C751.171 125.508 707.17-93.823 826.603 41.15c95.546 107.978 104.766 294.048 97.432 373.585L685.481 297.694l16.974 360.474-448.13-141.46Z" />
          <defs>
            <linearGradient id="60c3c621-93e0-4a09-a0e6-4c228a0116d8" x1="926.392" x2="-109.635" y1=".176" y2="321.024" gradientUnits="userSpaceOnUse">
              <stop stop-color="#776FFF" />
              <stop offset="1" stop-color="#FF4694" />
            </linearGradient>
          </defs>
        </svg>
      </div>
      <div class="relative mx-auto max-w-7xl py-24 sm:py-32 lg:px-8 lg:py-40">
        <div class="pl-6 pr-6 md:ml-auto md:w-2/3 md:pl-16 lg:w-1/2 lg:pl-24 lg:pr-0 xl:pl-32">
          <h2 class="text-base font-semibold leading-7 text-indigo-400">Nuestro equipo de expertos</h2>
          <p class="mt-2 text-3xl font-bold tracking-tight text-white sm:text-4xl">Estamos aquí para ayudarte</p>
          <p class="mt-6 text-base leading-7 text-gray-300">No esperes más y solicita el desarrollo o consultoría de software con nuestra empresa hoy mismo. Con nosotros, siempre te sentirás importante, querido y valorado. Nos basamos en relaciones comerciales a largo plazo, asegurando que tu éxito sea también el nuestro.</p>
          <div class="mt-8">
            <a href="https://wa.me/3322620459" class="inline-flex rounded-md bg-white/10 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-white/20 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-white">Contáctanos</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>


<script setup>
const people = [
  {
    name: 'Miguel Briseño',
    role: 'Co-Founder / CEO',
    imageUrl:
      'https://i.postimg.cc/Wb4sNjq8/miguel-removebg-preview.png'
  },
  {
    name: 'Daniel Montes',
    role: 'Co-Founder / COO',
    imageUrl:
      'https://i.postimg.cc/N0tpBC98/daniel.jpg'
  },
  {
    name: 'Leonardo Talavera',
    role: 'Co-Founder / CTO',
    imageUrl:
      'https://i.postimg.cc/4yrN99pG/Whats-App-Image-2024-05-23-at-15-31-42.jpg'
  },
]
</script>