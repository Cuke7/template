<template>
  <div class="flex grow items-center justify-around">
    <div class="flex flex-col space-y-4">
      <h1 class="font-mono text-9xl">Birbs 🐦</h1>
      <p class="pl-1 text-lg">
        A collection of birb pictures, taken with and without their consent*.
      </p>
      <NuxtLink to="./pictures">
        <button
          class="btn btn-primary flex items-center rounded-full px-6 w-fit"
        >
          <span>Stalk</span>
          <photoLogo class="h-8" /></button
      ></NuxtLink>
    </div>

    <img
      src="~/assets/pictures/DSC_0674.jpg"
      class="w-1/3 rounded-xl object-fill drop-shadow-[0_35px_35px_rgba(0,0,0,0.25)] hover:drop-shadow-xl"
    />

    <div class="absolute bottom-2 right-2">
      *No birbs were harmed during the process.
    </div>
  </div>
</template>
