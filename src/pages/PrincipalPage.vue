<script setup>
import Merchan from '@/assets/merchandasing.png'
</script>

<template>
  <section class="flex flex-col gap-4">
    <header>
      <h1 class="title-page">Portal do Cliente</h1>
      <p>Navegue por nossas soluções ou veja as últimas consultas</p>
    </header>

    <div class="content-section">
      <div class="content-card mx-auto w-1/2">
        <header>
          <h2 class="text-xl font-semibold">Lorem ipsum.</h2>
          <p>Lorem ipsum dolor sit amet, consectetur.</p>
        </header>

        <hr class="my-6 h-px border-0 bg-gray-200 dark:bg-gray-700" />

        <div class="content-card--body">
          <div v-for="i in 8" :key="i" class="flex flex-col items-center gap-4 p-4">
            <div
              class="flex size-16 items-center justify-center rounded-xl border bg-gray-100 shadow"
            >
              <svg
                width="40"
                height="32"
                viewBox="0 0 40 32"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M21.25 6L12.5 17.25H18.75V26L27.5 14.75H21.25V6V6Z"
                  stroke="#39B025"
                  stroke-width="1.5"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M31.1783 6C27.0319 1.366 20.4562 -0.229172 14.6473 1.9898C8.83842 4.20876 5.00093 9.78172 5 16V17.25"
                  stroke="#39B025"
                  stroke-width="1.5"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M8.82129 26C12.9677 30.634 19.5434 32.2292 25.3523 30.0102C31.1612 27.7912 34.9987 22.2183 34.9996 16V14.75"
                  stroke="#39B025"
                  stroke-width="1.5"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M31.25 18.5L35 14.75L38.75 18.5"
                  stroke="#39B025"
                  stroke-width="1.5"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M8.75 13.5L5 17.25L1.25 13.5"
                  stroke="#39B025"
                  stroke-width="1.5"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </div>

            <!-- app name -->

            <div class="text-sm font-semibold">Lorem ipsum</div>
          </div>
        </div>
      </div>

      <div class="mx-auto w-1/2">
        <img :src="Merchan" alt="Banner Merchan" class="w-full" />
      </div>

      <!-- cards -->

      <div class="content-card mx-auto w-1/2">
        <header>
          <h2 class="text-xl font-semibold">Lorem ipsum.</h2>
          <p>Lorem ipsum dolor sit amet, consectetur.</p>
        </header>

        <hr class="my-6 h-px border-0 bg-gray-200 dark:bg-gray-700" />

        <div class="content-card--body">
          <div v-for="i in 5" :key="i" class="flex flex-col items-center gap-4 p-4">
            <div
              class="flex size-16 items-center justify-center rounded-xl border bg-gray-100 shadow"
            >
              <svg
                width="40"
                height="32"
                viewBox="0 0 40 32"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M21.25 6L12.5 17.25H18.75V26L27.5 14.75H21.25V6V6Z"
                  stroke="#39B025"
                  stroke-width="1.5"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M31.1783 6C27.0319 1.366 20.4562 -0.229172 14.6473 1.9898C8.83842 4.20876 5.00093 9.78172 5 16V17.25"
                  stroke="#39B025"
                  stroke-width="1.5"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M8.82129 26C12.9677 30.634 19.5434 32.2292 25.3523 30.0102C31.1612 27.7912 34.9987 22.2183 34.9996 16V14.75"
                  stroke="#39B025"
                  stroke-width="1.5"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M31.25 18.5L35 14.75L38.75 18.5"
                  stroke="#39B025"
                  stroke-width="1.5"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M8.75 13.5L5 17.25L1.25 13.5"
                  stroke="#39B025"
                  stroke-width="1.5"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </div>

            <!-- app name -->

            <div class="text-sm font-semibold">Lorem ipsum</div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
