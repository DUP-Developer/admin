<template>
  <div class="max-w-sm w-1/2 h-auto lg:max-w-full lg:flex">
    <div
      class="h-48 lg:h-auto lg:w-48 flex-none bg-cover rounded-t lg:rounded-t-none lg:rounded-l text-center overflow-hidden"
      style="background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSE4HuKLY1QREYKxJ44QvYfbFLAmjMTTSxSkBwZAqRzEEBbaCSghw')"
      title="Woman holding a mug"
    ></div>
    <div
      class="border-r border-b border-l border-gray-400 lg:border-l-0 lg:border-t lg:border-gray-400 bg-white rounded-b lg:rounded-b-none lg:rounded-r p-4 flex flex-col justify-between leading-normal"
    >
      <div class="mb-8">
        <p class="text-sm text-red-600 flex items-center">
          <svg
            class="fill-current text-red-500 w-3 h-3 mr-2"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 20 20"
          >
            <path
              d="M4 8V6a6 6 0 1 1 12 0v2h1a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2v-8c0-1.1.9-2 2-2h1zm5 6.73V17h2v-2.27a2 2 0 1 0-2 0zM7 6v2h6V6a3 3 0 0 0-6 0z"
            />
          </svg>
          Status [open, closed, progress]
        </p>
        <div class="text-gray-900 font-bold text-xl mb-2">Name Projects</div>
        <p
          class="text-gray-700 text-base"
        >Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
      </div>
      <div class="flex justify-between items-center">
        <div class="text-sm">
          <p class="text-gray-900 leading-none">Cliente name</p>
          <p class="text-gray-600">10/05/2019 - 15/10/2020</p>
        </div>
        <div class="w-auto flex flex-row">
          <button
            class="mx-2 bg-transparent hover:bg-blue-500 text-blue-700 font-semibold hover:text-white py-2 px-4 border border-blue-500 hover:border-transparent rounded"
          >view</button>
          <button
            class="mx-2 bg-transparent hover:bg-blue-500 text-blue-700 font-semibold hover:text-white py-2 px-4 border border-blue-500 hover:border-transparent rounded"
          >proposal</button>          
          <div class="relative">
            <select
              class="appearance-none w-full border bg-transparent border-blue-500  hover:text-white hover:bg-blue-500 text-blue-700 py-3 px-4 pr-8 rounded focus:outline-none focus:border-blue-500"
              id="grid-state"
            >
              <option>Status</option>
              <option>Start</option>
              <option>Progress</option>
              <option>Closed</option>
            </select>
            <div
              class="pointer-events-none absolute inset-y-0 right-0 flex items-center px-2 text-gray-700"
            >
              <svg
                class="fill-current h-4 w-4"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
              >
                <path
                  d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
                />
              </svg>
            </div>
          </div>          
          <button
            class="mx-2 bg-transparent hover:bg-red-500 text-red-700 font-semibold hover:text-white py-2 px-4 border border-red-500 hover:border-transparent rounded"
          >delete</button>
        </div>
      </div>
    </div>
  </div>
</template>