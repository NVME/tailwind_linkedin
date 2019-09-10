<template>
  <a href="#" class="flex py-4 px-2">
    <img
      class="h-10 w-10"
      :src="pic"
      
    />
    <div class="px-4">
      <h3 class="text-sm font-semibold hover:underline hover:text-blue-600">{{name}}</h3>
      <span class="block text-xs text-gray-800 ">{{followers}}followers</span>
      <span class="block text-xs text-gray-800 ">{{time}}</span>
    </div>
  </a>
</template>
<script>
export default {
    props:[
        'name',
        'followers',
        'time',
        'pic'

    ]
}
</script>