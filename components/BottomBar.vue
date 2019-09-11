<template>
  <div class="fixed inset-x-0 bottom-0 h-20 bar-color flex flex-row">
    <div class="w-24 h-24 rounded-full ml-8 -mt-8 border-gray-800 border-4">
      <img
        class="object-cover rounded-full"
        src="https://avatars2.githubusercontent.com/u/7293460?s=460&v=4"
        alt
      />
    </div>
    <div class="flex justify-center w-screen py-6">
      <a href="/" class="cursor-pointer hover:text-gray-500 text-white px-4">HOME</a>
      <a href="/projects/list" class="cursor-pointer hover:text-gray-500 text-white px-4">PROJECTS</a>
      <a href="/diagrams" class="cursor-pointer hover:text-gray-500 text-white px-4">GRAPH</a>
    </div>
  </div>
</template>

<style lang="css">
.border-gray-800 {
  border-color: #2D2D2D;
}
</style>