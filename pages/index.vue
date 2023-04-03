<template>
  <div>
    <Head>
      <Title
        >Bizenforce - Grow your business with world leading AI driven tools and technologies</Title
      >
      <Meta
        name="description"
        content="Grow your business with world leading AI driven tools and technologies"
      />
    </Head>

    <section class="bg-[url(~/assets/bg.jpeg)] bg-cover">
      <div className="flex justify-center items-center backdrop-brightness-50">
        <div class="mx-auto px-3 w-full md:max-w-5xl py-16 md:py-32">
          <h1
            class="text-4xl text-center pt-8 md:text-7xl font-extrabold text-white"
          >
            Grow your business with world leading AI driven tools and
            technologies.
          </h1>
        </div>
      </div>
    </section>

    <section
      class="mx-auto md:max-w-7xl py-4 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
    >
      <div>
        <div>
          <h1 class="text-6xl text-center py-8 md:text-7xl font-extrabold">
            What is AI?
          </h1>
          <p class="text-gray-600 text-md md:text-2xl text-center">
            AI stands for an
            <span class="font-bold italic">Artificial Intelligence</span>, broad
            field of computer science that involves the development of
            intelligent machines that can perform tasks that typically require
            human-level intelligence, such as visual perception, speech
            recognition, decision-making, and language translation. AI systems
            are designed to learn from experience and adapt to new situations,
            improving their performance over time.
          </p>
          <p
            class="font-semibold text-center text-md md:text-2xl py-3 text-gray-900"
          >
            Here are some of the main areas of AI:
          </p>
          <div class="py-2 grid grid-cols-1 md:grid-cols-3 gap-4">
            <div
              v-for="(ai, i) in aiTypes"
              :key="i"
              class="border border-gray-100 h-full rounded p-5 hover:bg-gray-100"
            >
              <div class="flex items-center h-full">
                <div>
                  <h2
                    class="font-semibold text-xl md:text-2xl py-2 text-center"
                  >
                    {{ ai.title }}
                  </h2>
                  <p class="text-center text-gray-600">{{ ai.subtitle }}.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="bg-gray-200">
      <div
        class="mx-auto md:max-w-7xl py-4 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
      >
        <div class="pt-16">
          <h1
            class="text-6xl text-center pt-8 md:text-7xl font-extrabold text-gray-900"
          >
            How AI impacts the world?
          </h1>
          <div class="w-16 mx-auto border-t-4 border-blue-600 mb-8 mt-2"></div>
          <p class="text-gray-600 text-lg md:text-2xl py-2 text-center">
            AI (Artificial Intelligence) is already having a significant impact
            on the world with technology. It is revolutionizing numerous
            industries and transforming the way we live and work. Some of the
            areas where AI is influencing the world include:
          </p>
          <div class="md:flex md:space-x-10 md:justify-center md:items-center">
            <div class="w-full md:w-1/2">
              <ul class="list-decimal pl-5">
                <li
                  v-for="(ai, i) in aiInfluences"
                  :key="i"
                  class="py-1 text-gray-600"
                >
                  <span class="font-bold">{{ ai.title }}</span
                  >: {{ ai.subtitle }}
                </li>
              </ul>
            </div>
            <div class="w-full max-w-[400px]">
              <img
                src="../assets/mj1.jpeg"
                alt="Bizenforce AI Tips"
                class="max-h-[500px] rounded"
              />
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts">
import aiTypes from "~~/data/ai.types";
import aiInfluences from "~~/data/ai.influences";
</script>
