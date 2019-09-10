<template>
  <div class="bg-white mt-2 border border border-grey rounded shadow">
  
    <div>
      <div class="flex justify-between px-2">
        <actor
           pic="https://media.licdn.com/dms/image/C4D0BAQEzfzd-1PYMuA/company-logo_100_100/0?e=1576108800&v=beta&t=HCe603Tm7BpjRnNg5hdKY6oD1uog9YskweI13UBuAwo"
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
       <img src="https://media-exp1.licdn.com/media-proxy/ext?w=800&h=800&f=pj&hash=rnIVMKCHiB57NOmKm3TGvbJC7yg%3D&ora=1%2CaFBCTXdkRmpGL2lvQUFBPQ%2CxAVta5g-0R6jnhodx1Ey9KGTqAGj6E5DQJHUA3L0CHH05IbfPWjpfsTdKuGnpUAWKy8EjQA2Lbu1SDHlQ47vf4zsddl02sK3cpD5agYUbhl4j3lK6w&shareType=image" height="314.13612565445027" width="600">
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