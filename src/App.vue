<template>
  <div id="app" class="bg-grey-lightest w-full font-sans">
    <top-nav class="" />
    <div class="py-4 px-64 flex items-center">
      <a href="#" class="underline  font-semibold text-sm">
        <span class="text-blue-600">Start building on Windows</span>
        -
        <span class="text-gray-700">You can now use Windows, Linux, and macOS jobs all in a single workflow.</span>
      </a>
      <span class="text-xs text-gray-700 px-2">Ad</span>
      <a href="#" class="inline-block ">
        <svg class="fill-current h-4 w-4">
          <path d="M2,7H4V9H2V7ZM7,9H9V7H7V9Zm5-2V9h2V7H12Z" />
        </svg>
      </a>
    </div>
     <div class="px-28 flex justify-center">
   
       
       <section class="w-2/10 flex-col ">       
          <profile/>
          <recent/>
          
       </section>
       <section class="w-5/10 ml-6 mb-10">       
        <new-post/>
        <dxc/>
        <hpe/>
        <hp/>
       </section>
       <section class="w-3/10 ml-6">
         <right/>

       </section>
     </div>
  </div>
</template>

<script>
import TopNav from "./components/TopNav.vue";
import Profile from './components/Profile.vue'
import Recent from './components/Recent.vue'
import NewPost from './components/New.vue'
import Hpe from './components/HPE.vue'
import Dxc from './components/DXC.vue'
import Hp from './components/HP.vue'
import Right from './components/Right.vue'
export default {
  name: "app",
  components: {
    TopNav,
    Profile,
    Recent,
    NewPost,
    Hpe,
    Dxc,
    Hp,
    Right
  }
};
</script>

