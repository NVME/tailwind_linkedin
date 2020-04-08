<template>
  <div class="bg-white mt-2 border border border-grey rounded shadow">
    <div class="flex justify-between pt-2 px-4 border-b border-grey-lighter">
      <div>
        <a
          href="#"
          class="text-xs text-gray-900 hover:text-blue-600 hover:underline font-semibold"
        >Gregory Epstein</a>
        <span class="text-xs text-gray-700">&#32;likes this</span>
      </div>
      <svg class="fill-current h-6 w-6">
        <path d="M2,10H6v4H2V10Zm8,4h4V10H10v4Zm8-4v4h4V10H18Z" />
      </svg>
    </div>
    <div>
      <div class="flex justify-between px-2">
        <actor
          pic="https://media-exp1.licdn.com/dms/image/C4E0BAQFs5HVdyuXuww/company-logo_100_100/0?e=1594252800&v=beta&t=kFVvKHEYVMMAJp2ez-CyvdKoUcr4yOy8BcPnjWGojVo"
          name="DXC Technology"
          followers="869,796"
          time="3d"
        />
        <button class="inline-block text-blue-600 text-md font-semibold">
          <span class="inline-block py-2 px-2 hover:bg-blue-200 rounded">
            <svg class="inline-block fill-current h-4 w-4">
              <path d="M14,9H9v5H7V9H2V7H7V2H9V7h5V9Z" class="small-icon" style="fill-opacity: 1" />
            </svg>
            Follow
          </span>
        </button>
      </div>
      <div>
        <p class="px-4 pb-4 text-sm">
          The key for a podcast to endure is to offer something of value. Here’s Chris Nerney's take on how to build an audience for your podcast to raise your profile and advance in your career:
          <a
            href="#"
            class="text-blue-600 hover:underline font-semibold"
          >https://dxc.to/2MHsMGs</a>
        </p>
        <img
          src="https://media-exp1.licdn.com/media-proxy/ext?w=800&amp;h=800&amp;f=pj&amp;hash=bGHqag1kjfUEV2xauCtJRIshRjk%3D&amp;ora=1%2CaFBCTXdkRmpGL2lvQUFBPQ%2CxAVta5g-0R6jnhodx1Ey9KGTqAGj6E5DQJHUA3L0CHH05IbfPWi9K8PYfbDz9kBCKi9UjQA3fOu1EWSzFI7uformeo122cPldcP5agYUbhl4lWdI&amp;shareType=image"
          class="ivm-view-attr__img-wrapper--custom-img ivm-view-attr__img--centered feed-shared-image__image feed-shared-image__image--constrained"
          alt="No alternative text description for this image"
          height="314.13612565445027"
          width="600"
        />
      </div>
    </div>
    <comment vote="81" comments="4" />
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