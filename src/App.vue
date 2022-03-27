<script setup></script>

<template>
  <div class="flex w-screen min-h-screen">
    <div class="w-1/2 p-16">
      <div class="mt-32">
        <h1
          class="font-bold text-transparent text-7xl bg-clip-text bg-gradient-to-br from-green-400 to-green-600"
          id="heading"
        >
          Explore and share your observations from nature
        </h1>
        <p class="mt-8 text-lg text-gray-600" id="description">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sint
          temporibus similique id impedit voluptatem optio unde iusto, nisi
          animi dolorum repellendus assumenda ea maiores expedita necessitatibus
          vitae cum sapiente perspiciatis eos accusamus illo magni eligendi
          nihil velit? Optio pariatur, rem reprehenderit odio sequi neque
          repudiandae voluptatum in voluptatem doloremque eligendi.
        </p>
        <div class="flex mt-16">
          <button
            class="main-btn w-48 p-4 text-white rounded-lg shadow-lg bg-gradient-to-br from-green-200 via-green-400 to-green-500 shadow-green-400/60"
          >
            <p class="text-lg font-semibold">Explore nature</p>
          </button>
          <button
            class="main-btn w-48 p-4 ml-4 text-green-500 border-2 border-green-400 rounded-lg shadow-lg shadow-green-400/60"
          >
            <p class="text-lg font-semibold">Learn more</p>
          </button>
        </div>
        <div class="mt-16">
          <div
            id="downArrow"
            class="flex items-center justify-center w-16 h-16 rounded-full shadow-lg shadow-green-400/60 bg-gradient-to-br from-green-200 via-green-400 to-green-500"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="currentColor"
              class="w-8 h-8 text-white"
              viewBox="0 0 16 16"
            >
              <path
                fill-rule="evenodd"
                d="M8 1a.5.5 0 0 1 .5.5v11.793l3.146-3.147a.5.5 0 0 1 .708.708l-4 4a.5.5 0 0 1-.708 0l-4-4a.5.5 0 0 1 .708-.708L7.5 13.293V1.5A.5.5 0 0 1 8 1z"
              />
            </svg>
          </div>
        </div>
      </div>
    </div>

    <div class="relative w-1/2 p-16">
      <div
        class="absolute inset-0 bg-gradient-to-br from-green-200 via-green-400 to-green-500 blur-xl"
      ></div>
      <div
        class="relative z-10 grid grid-cols-12 mt-24"
        style="grid-template-rows: 150px 1fr"
      >
        <img
          class="col-span-5 rounded-lg"
          src="/image1.jpg"
          alt="Large waterfall in the mountains"
          id="imageLeft"
        />
        <img
          class="col-span-5 col-start-5 rounded-lg"
          src="/image2.jpg"
          alt="Misty pathway through a forest"
          id="imageRight"
        />
      </div>
    </div>
  </div>
</template>

<style></style>
