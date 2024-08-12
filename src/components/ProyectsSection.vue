<template>
  <div class="bg-white py-10 sm:py-32">
    
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <div class="mx-auto max-w-2xl text-center">
        <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Echale un ojo a lo que hacemos para nuestros clientes</h2>
        <p class="mt-2 text-lg leading-8 text-gray-600">Conocenos atravez de nuestra experiencia.</p>
      </div>
      <stats-section class="py-10"></stats-section>
      <div class="mx-auto mt-16 grid max-w-2xl auto-rows-fr grid-cols-1 gap-8 sm:mt-20 lg:mx-0 lg:max-w-none lg:grid-cols-2">
        <article v-for="post in posts" :key="post.id" class="relative isolate flex flex-col justify-end overflow-hidden rounded-2xl bg-gray-900 px-8 pb-8 pt-80 sm:pt-48 lg:pt-80">
          <img :src="post.imageUrl" alt="" class="absolute inset-0 -z-10 h-full w-full object-cover" />
          <div class="absolute inset-0 -z-10 bg-gradient-to-t from-gray-900 via-gray-900/40" />
          <div class="absolute inset-0 -z-10 rounded-2xl ring-1 ring-inset ring-gray-900/10" />

          <div class="flex flex-wrap items-center gap-y-1 overflow-hidden text-sm leading-6 text-gray-300">
            <time :datetime="post.datetime" class="mr-8">{{ post.date }}</time>
            <div class="-ml-4 flex items-center gap-x-4">
              <svg viewBox="0 0 2 2" class="-ml-0.5 h-0.5 w-0.5 flex-none fill-white/50">
                <circle cx="1" cy="1" r="1" />
              </svg>
              <div class="flex gap-x-2.5">
                <img :src="post.author.imageUrl" alt="" class="h-6 w-6 flex-none rounded-full bg-white/10" />
                {{ post.author.name }}
              </div>
            </div>
          </div>
          <h3 class="mt-3 text-lg font-semibold leading-6 text-white">
            <a >
              <span class="absolute inset-0" />
              {{ post.title }}
            </a>
          </h3>
        </article>
      </div>
    </div>
  </div>
</template>

<script setup>
import imagen from '../assets/portfolio/1.png'
import imagen2 from '../assets/portfolio/2.png'
import imagen3 from '../assets/portfolio/3.png'
import imagen4 from '../assets/portfolio/4.png'
import imagen5 from '../assets/portfolio/5.png'
import logo1 from '../assets/justLogos/1.png'
import logo2 from '../assets/justLogos/2.png'
import logo3 from '../assets/justLogos/3.png'
import logo4 from '../assets/justLogos/4.png'
import logo5 from '../assets/justLogos/5.png'




import StatsSection from './StatsSection.vue';

const posts = [
  {
    id: 1,
    title: 'Azul ERP',
    href: '#',
    description:
      'Illo sint voluptas. Error voluptates culpa eligendi. Hic vel totam vitae illo. Non aliquid explicabo necessitatibus unde. Sed exercitationem placeat consectetur nulla deserunt vel. Iusto corrupti dicta.',
    imageUrl:
      imagen,
    date: 'Mar 16, 2020',
    datetime: '2020-03-16',
    author: {
      name: 'Destiladora Agave Azul',
      imageUrl:
        logo1,
    },
  },
  {
    id: 2,
    title: 'Lion´s Protection',
    href: '#',
    description:
      'Illo sint voluptas. Error voluptates culpa eligendi. Hic vel totam vitae illo. Non aliquid explicabo necessitatibus unde. Sed exercitationem placeat consectetur nulla deserunt vel. Iusto corrupti dicta.',
    imageUrl:
      imagen2,
    date: 'Mar 16, 2020',
    datetime: '2020-03-16',
    author: {
      name: 'Aseguradora Vehicular Lion´s protection',
      imageUrl:
        logo2,
    },
  },
  {
    id: 3,
    title: 'OAKLAND.net',
    href: '#',
    description:
      'Illo sint voluptas. Error voluptates culpa eligendi. Hic vel totam vitae illo. Non aliquid explicabo necessitatibus unde. Sed exercitationem placeat consectetur nulla deserunt vel. Iusto corrupti dicta.',
    imageUrl:
      imagen3,
    date: 'Mar 16, 2020',
    datetime: '2020-03-16',
    author: {
      name: 'OAKLAND Ferretera',
      imageUrl:
        logo3,
    },
  },
  {
    id: 4,
    title: 'DRYWAPP',
    href: '#',
    description:
      'Illo sint voluptas. Error voluptates culpa eligendi. Hic vel totam vitae illo. Non aliquid explicabo necessitatibus unde. Sed exercitationem placeat consectetur nulla deserunt vel. Iusto corrupti dicta.',
    imageUrl:
      imagen4,
    date: 'Mar 16, 2020',
    datetime: '2020-03-16',
    author: {
      name: 'DRYWAPP Aplication',
      imageUrl:
        logo4,
    },
  },
  {
    id: 5,
    title: 'TECHREO ',
    href: '#',
    description:
      'Illo sint voluptas. Error voluptates culpa eligendi. Hic vel totam vitae illo. Non aliquid explicabo necessitatibus unde. Sed exercitationem placeat consectetur nulla deserunt vel. Iusto corrupti dicta.',
    imageUrl:
      imagen5,
    date: 'Mar 16, 2020',
    datetime: '2020-03-16',
    author: {
      name: 'TECHREO',
      imageUrl:
        logo5,
    },
  },
  // More posts...
]
</script>