<template>
  <div class="bg-white mt-2 border border border-grey rounded shadow">
    <div class="py-4 ">
      <toggle  title="Recent" active="true">
        <div class=" pb-4" >
          <a href="#" class="block pl-4 text-gray-600 hover:underline hover:bg-gray-300 ">
            <svg class=" inline-block fill-current h-4 w-4" focusable="false"><path d="M15.11,9.41L13.37,8.25l0.41-.83A2,2,0,0,0,14,6.53v-1a1.5,1.5,0,0,0-3,0v1a2,2,0,0,0,.21.89l0.41,0.83-0.07,0-0.21-.13L9,7V6.5H9L9.33,6A4,4,0,0,0,10,3.79V3.11A2.07,2.07,0,0,0,8.34,1,2,2,0,0,0,6,3V3.79A4,4,0,0,0,6.67,6L7,6.5H7V7L4.66,8.17,4.45,8.3l-0.07,0,0.41-.83A2,2,0,0,0,5,6.53v-1a1.5,1.5,0,0,0-3,0v1a2,2,0,0,0,.21.89L2.63,8.25,0.89,9.41A2,2,0,0,0,0,11.07V14a1,1,0,0,0,1,1H15a1,1,0,0,0,1-1V11.07A2,2,0,0,0,15.11,9.41ZM3,10.73V13H2V10.95l1-.69A3,3,0,0,0,3,10.73ZM11,13H5V10.73a1,1,0,0,1,.55-0.89L8,8.61l2.45,1.22a1,1,0,0,1,.55.89V13Zm3,0H13V10.73c0-.16,0-0.48,0-0.48l1,0.69V13Z" ></path></svg>
            <span class="inline-block pl-2 font-semibold text-xs text-gray-600 ">.NET Developer Pro</span>
          </a>
          <a href="#" class="block pl-4 text-gray-600 hover:underline hover:bg-gray-300">
            <svg class="inline-block fill-current h-4 w-4" focusable="false"><path d="M13,7V5H11.43L12,1H10.12L9.55,5H7.3l.58-4H6L5.43,5H3V7H5.14L4.86,9H3v2H4.57L4,15H5.88l.57-4H8.7l-.58,4H10l.57-4H13V9H10.86l.28-2ZM9,9H6.73L7,7H9.27Z" ></path></svg>
            <span class="inline-block pl-2 font-semibold text-xs text-gray-600 ">自媒体</span>
          </a>
          <a href="#" class="block pl-4 text-gray-600 hover:underline hover:bg-gray-300">
              <svg class="inline-block fill-current h-4 w-4" focusable="false"><path d="M13,7V5H11.43L12,1H10.12L9.55,5H7.3l.58-4H6L5.43,5H3V7H5.14L4.86,9H3v2H4.57L4,15H5.88l.57-4H8.7l-.58,4H10l.57-4H13V9H10.86l.28-2ZM9,9H6.73L7,7H9.27Z" ></path></svg>
              <span class="inline-block pl-2 font-semibold text-xs text-gray-600 ">前瞻媒体</span>
         </a>
          <a href="#" class="block pl-4 text-gray-600 hover:underline hover:bg-gray-300">
            <svg class=" inline-block fill-current h-4 w-4 text-gray-600" focusable="false"><path d="M15.11,9.41L13.37,8.25l0.41-.83A2,2,0,0,0,14,6.53v-1a1.5,1.5,0,0,0-3,0v1a2,2,0,0,0,.21.89l0.41,0.83-0.07,0-0.21-.13L9,7V6.5H9L9.33,6A4,4,0,0,0,10,3.79V3.11A2.07,2.07,0,0,0,8.34,1,2,2,0,0,0,6,3V3.79A4,4,0,0,0,6.67,6L7,6.5H7V7L4.66,8.17,4.45,8.3l-0.07,0,0.41-.83A2,2,0,0,0,5,6.53v-1a1.5,1.5,0,0,0-3,0v1a2,2,0,0,0,.21.89L2.63,8.25,0.89,9.41A2,2,0,0,0,0,11.07V14a1,1,0,0,0,1,1H15a1,1,0,0,0,1-1V11.07A2,2,0,0,0,15.11,9.41ZM3,10.73V13H2V10.95l1-.69A3,3,0,0,0,3,10.73ZM11,13H5V10.73a1,1,0,0,1,.55-0.89L8,8.61l2.45,1.22a1,1,0,0,1,.55.89V13Zm3,0H13V10.73c0-.16,0-0.48,0-0.48l1,0.69V13Z" ></path></svg>
            <span class="inline-block pl-2 inline-block pl-2 font-semibold text-xs text-gray-600 ">.NET People</span>
          </a>
        </div>
      </toggle>
      <toggle title="Groups"></toggle>
      <toggle title="Followed Hashtags"></toggle>
    </div>
    <div class="border-t border-gray-500 text-center">
      <a href="#" class="py-3 block text-xs font-semibold">Discover more</a>
    </div>
  </div>
</template>

<script>
import Toggle from "./Toggle.vue";
export default {
  components: {
    Toggle
  }
};
</script>

