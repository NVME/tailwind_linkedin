<template>
  <div class=" flex justify-between items-center">
    <div class="px-2 py-1 flex">
      <a class="no-underline hover:underline hover:text-blue visited:text-gray-600" href="#">
        <img
          :src="pic"
          class="rounded-full h-12 w-12"
          alt
        />
      </a>

      <div class="py-2 px-2 text-gray-600 leading-tight">
        <span class="block text-gray-800 text-sm font-semibold">{{name}}</span>
        <span class="block text-xs">{{title}}</span>
      </div>
    </div>
    <a class="no-underline text-grey-dark font-semibold" href="#">
      <div
        class="mr-4 px-2 py-1 border border-blue-600 rounded-sm text-blue-600 hover:border-4 hover:bg-gray-200 hover:border-blue-800"
      >+ Follow</div>
    </a>
  </div>
</template>
<script>
export default {
    props:[
        'name',
        'title',
        'pic'
    ]
}
</script>