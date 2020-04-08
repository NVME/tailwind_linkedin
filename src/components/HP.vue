<template>
  <div class="bg-white mt-2 border border border-grey rounded shadow">
    <div>
      <div class="flex justify-between px-2">
        <actor
          pic="https://media-exp1.licdn.com/dms/image/C560BAQHIfx8v77vIVg/company-logo_100_100/0?e=1594252800&v=beta&t=6HiNPLO_Z9oZ0NAvrwdvyQUf3Ui8pWgm1z8o4rO1MI8"
          name="HP"
          followers="3,264,857"
          time="3m"
        />
        <svg class="fill-current h-6 w-6 text-gray-700 pt-2">
          <path d="M2,10H6v4H2V10Zm8,4h4V10H10v4Zm8-4v4h4V10H18Z" />
        </svg>
      </div>
      <div>
        <p
          class="px-4 pb-4 text-sm"
        >Using 3D by HP, SmileDirectClub is disrupting the orthodontics industry, by giving millions of customers access to affordable, high-quality teeth straightening.</p>
        <img
          src="https://media-exp1.licdn.com/media-proxy/ext?w=600&h=337&f=pj&hash=PNgAfTYIaqhWJMhOIHHmJB%2BRMJc%3D&ora=1%2CaFBCTXdkRmpGL2lvQUFBPQ%2CxAVta5g-0R66gRQekFEy8LyCqUH95VRUQJbPTHPhGXz0oYnCfiS2JNjaebehrUJTOHBewVBnK_LoAmWnS8b7NozodYoljMLhOcW2NVFLPU4z0iQXvNRqdEh04Mz3Vu6nNCsYgKEJOH7qYe-6MQRpRC8n-g&shareType=article"
          height="314.13612565445027"
          width="600"
        />
      </div>
      <div class="bg-gray-200 px-4 py-4 leading-tight">
        <a href="#">
          <span
            class="font-semibold text-sm"
          >SmileDirectClub plans to 3D print 50,000 teeth-straightening molds a day - TechCrunch</span>
          <h3 class="text-xs text-gray-600 py-1">social.techcrunch.com</h3>
        </a>
      </div>
    </div>
    <comment vote="1,100" comments="18" />
  </div>
</template>
<script>
import Actor from "./Actor.vue";
import Comment from "./Comment.vue";
export default {
  components: {
    Actor,
    Comment
  }
};
</script>