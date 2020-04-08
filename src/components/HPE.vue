<template>
  <div class="bg-white mt-2 border border border-grey rounded shadow">
  
    <div>
      <div class="flex justify-between px-2">
        <actor
           pic="https://media-exp1.licdn.com/dms/image/C4D0BAQEzfzd-1PYMuA/company-logo_100_100/0?e=1594252800&v=beta&t=NIviEapk_bfBD4vs5JaFT66QNex2CmDz1DOH_lf9nHg"
           name="Hewlett Packard Enterprise"
           followers="2,950,380" 
           time="2d"
         />
        <svg class="fill-current h-6 w-6 text-gray-700 pt-2">
        <path d="M2,10H6v4H2V10Zm8,4h4V10H10v4Zm8-4v4h4V10H18Z" />
      </svg>
      </div>
      <div>
        <p class="px-4 pb-4 text-sm">
        In the <span class="text-blue-600 font-semibold">  #BelgianGP</span> this weekend, our 
        <span class="text-blue-600 font-semibold"> #F1 </span> Mercedes-AMG Petronas Motorsport will fuel the right decisions with big data. Learn about technology at high speed: 
        <a href="#" class="text-blue-600 hover:underline font-semibold">http://hpe.to/6008EfKS0</a>
        </p>
       <img src="https://media-exp1.licdn.com/dms/image/C4D22AQHlBz8e8jaGcg/feedshare-shrink_800/0?e=1589414400&v=beta&t=c-L68OeFTjp6q3jLMCjngMmoAA056ltSvzsW0SO6r0g" height="314.13612565445027" width="600">
      </div>
    </div>
    <comment vote="216" comments="32"/>
  </div>
</template>
<script>
import Actor from "./Actor.vue";
import Comment from "./Comment.vue"
export default {
  components: {
    Actor,
    Comment
  }
};
</script>