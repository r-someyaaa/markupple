<!-- Please remove this file from your project -->
<template>
  <div class="relative flex justify-center min-h-screen bg-orange-50 items-center sm:pt-0">
    <script src="https://cdn.tailwindcss.com"></script>
    <div class="max-w-4xl mx-auto sm:px-6 lg:px-8">
      <h2 class="text-2xl text-center leading-7 text-black font-bold font-heebo">
        Welcome to
      </h2>
      <div class="flex justify-center pt-8 sm:pt-0">
        <img width="340" src="@/assets/images/common/logo_text.svg" alt="">
      </div>
      <div class="mt-0 text-center overflow-hidden p-6">
        <div class="mt-16">
          <nuxt-link to="/editor" class="inline-flex items-center rounded-md bg-red-600 px-3 py-2 text-sm font-semibold text-white shadow-sm">
            エディターを開く
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="-mr-0.5 ml-1.5 h-5 w-5"><path fill="currentColor" d="M5 21q-.825 0-1.413-.588T3 19V5q0-.825.588-1.413T5 3h7v2H5v14h14v-7h2v7q0 .825-.588 1.413T19 21H5Zm4.7-5.3l-1.4-1.4L17.6 5H14V3h7v7h-2V6.4l-9.3 9.3Z"/></svg>
          </nuxt-link>
        </div>
      </div>
      <div class="flex justify-center pt-4 space-x-2">
        <a href="https://github.com/r-someyaaa/markupple" target="_blank"><svg
          class="w-6 h-6 text-orange-950 hover:text-gray-800 button--github"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          aria-hidden="true"
          role="img"
          width="32"
          height="32"
          preserveAspectRatio="xMidYMid meet"
          viewBox="0 0 24 24"
        ><path d="M12 2.247a10 10 0 0 0-3.162 19.487c.5.088.687-.212.687-.475c0-.237-.012-1.025-.012-1.862c-2.513.462-3.163-.613-3.363-1.175a3.636 3.636 0 0 0-1.025-1.413c-.35-.187-.85-.65-.013-.662a2.001 2.001 0 0 1 1.538 1.025a2.137 2.137 0 0 0 2.912.825a2.104 2.104 0 0 1 .638-1.338c-2.225-.25-4.55-1.112-4.55-4.937a3.892 3.892 0 0 1 1.025-2.688a3.594 3.594 0 0 1 .1-2.65s.837-.262 2.75 1.025a9.427 9.427 0 0 1 5 0c1.912-1.3 2.75-1.025 2.75-1.025a3.593 3.593 0 0 1 .1 2.65a3.869 3.869 0 0 1 1.025 2.688c0 3.837-2.338 4.687-4.563 4.937a2.368 2.368 0 0 1 .675 1.85c0 1.338-.012 2.413-.012 2.75c0 .263.187.575.687.475A10.005 10.005 0 0 0 12 2.247z" fill="currentColor" /></svg></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NuxtTutorial'
}
</script>
