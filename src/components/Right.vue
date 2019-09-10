<template>
  <div class="bg-white border border border-grey rounded shadow">
    <div class="flex justify-between items-center pt-6 px-4">
      <span class="text-md">Add to your feed</span>
      <svg
        viewBox="0 0 24 24"
        width="24px"
        height="24px"
        x="0"
        y="0"
        preserveAspectRatio="xMinYMin meet"
        class="fill-current text-gray-600"
        focusable="false"
      >
        <path
          d="M7,7h2v5H7V7zM15,8c0,3.9-3.1,7-7,7c-3.9,0-7-3.1-7-7c0-3.9,3.1-7,7-7C11.9,1,15,4.1,15,8zM13.2,8c0-2.9-2.3-5.2-5.2-5.2C5.1,2.8,2.8,5.1,2.8,8c0,2.9,2.3,5.2,5.2,5.2C10.9,13.2,13.2,10.9,13.2,8zM7,6h2V4H7V6z"
        />
      </svg>
    </div>
    <div class="py-4">
      <recommend
        name="Jeff Weiner"
        title="CEO at Linkedin"
        pic="https://media.licdn.com/dms/image/C4D03AQFM3Y2r-OEStw/profile-displayphoto-shrink_100_100/0?e=1573689600&amp;v=beta&amp;t=FENIASyNJfuRK1rscrtitDmqHM0IDbsJMJuEpOCDgFY"
      />
      <recommend
        name="Craig Brown, PhD"
        title="I.T. Thought Leadership"
        pic="https://media.licdn.com/dms/image/C5603AQHq_R7a3rNrdg/profile-displayphoto-shrink_100_100/0?e=1573689600&v=beta&t=Fhe-K_sR2Tf2Shs1q2RIXUlRYH6Uz533drRootP1yWM"
      />
      <div class="px-4 py-4 border-b border-grey">
        <a href="#"  class="text-blue-700 font-semibold text-sm">View all recommendations</a>
      </div>
      <ads/>
      <linkedin/>
    </div>
  </div>
</template>

<script>
import Recommend from "./Recommend.vue";
import Ads from "./Ads.vue"
import Linkedin from "./Linkedin"
export default {
  components: {
    Recommend,
    Ads,
    Linkedin
  }
};
</script>