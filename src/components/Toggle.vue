<template>
  <div > 
    <div class="flex justify-between hover:bg-gray-300">
     
    <span v-if='active' class="pl-4 text-xs font-semibold text-gray-900 ">{{title}}</span>    
       
      <a v-else href="#">
          <span class="pl-4 text-xs font-semibold text-blue-600 ">{{title}}</span>
      </a>
     
      <span v-if='active'>
        <svg
          class="h-4 w-4 fill-current text-gray-500 hidden hover:block"
        >
          <path d="M8,9l5.93-4L15,6.54l-6.15,4.2a1.5,1.5,0,0,1-1.69,0L1,6.54,2.07,5Z" />
        </svg>
      </span>
    </div>
    <div>
        <slot/>
    </div>
  </div>
</template>
<script>
export default {
    props:{
       title:{
           required:true
       },
       active:{
           default:false
       }
    }
}
</script>

