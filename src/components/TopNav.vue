<template>
  <header class="bg-linkedin-blue py-2 ">
    <nav class="px-28 flex items-center">
      <div class="w-1/3 flex justify-center">
        <a href="#" class="block rounded-xl pr-2">
          <logo></logo>
        </a>
        <div class="w-full ml-1 flex relative">
          <input
            type="text"
            class="w-full h-logo bg-gray-300 text-black text-sm py-2 pl-8 rounded-sm placeholder-gray-900"
            placeholder="Search"
          />
          <div class="pointer-events-none absolute inset-y-0 left-0 pl-2 flex items-center">
            <svg
              class="fill-current pointer-events-none text-gray-900 w-4 h-4"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 20 20"
            >
              <path
                d="M12.9 14.32a8 8 0 1 1 1.41-1.41l5.35 5.33-1.42 1.42-5.33-5.34zM8 14A6 6 0 1 0 8 2a6 6 0 0 0 0 12z"
              />
            </svg>
          </div>
        </div>
      </div>
      <div class="w-2/3 flex justify-center pl-20 items-center">
        <div class="flex-1 text-center text-white text-xs border-b-2 border-white -mb-2">
          <a href="#" class="inline-block ">
            <span class="inline-block -mb-1">
              <svg
                class="fill-current"
                viewBox="0 0 24 24"
                width="24px"
                height="24px"
                x="0"
                y="0"
                focusable="false"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M22,8.45L12.85,2.26a1.5,1.5,0,0,0-1.69,0L2,8.45,3.06,10,4,9.37V19a1,1,0,0,0,1,1h5V15h4v5h5a1,1,0,0,0,1-1V9.37L20.94,10Z"
                />
              </svg>
            </span>
            <p>Home</p>
          </a>
        </div>
        <div
          class="flex-1 text-center text-gray-400 text-xs border-b-2 border-transparent border-b-2 border-transparent -mb-2"
        >
          <a href="#" class="block">
            <span class="inline-block -mb-1">
              <svg
                viewBox="0 0 24 24"
                width="24px"
                height="24px"
                x="0"
                y="0"
                focusable="false"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M20.74,14.2L19,13.54V12.86l0.25-.41A5,5,0,0,0,20,9.82V9a3,3,0,0,0-6,0V9.82a5,5,0,0,0,.75,2.63L15,12.86v0.68l-1,.37a4,4,0,0,0-.58-0.28l-2.45-1V10.83A8,8,0,0,0,12,7V6A4,4,0,0,0,4,6V7a8,8,0,0,0,1,3.86v1.84l-2.45,1A4,4,0,0,0,0,17.35V20a1,1,0,0,0,1,1H22a1,1,0,0,0,1-1V17.47A3.5,3.5,0,0,0,20.74,14.2ZM16,8.75a1,1,0,0,1,2,0v1.44a3,3,0,0,1-.38,1.46l-0.33.6a0.25,0.25,0,0,1-.22.13H16.93a0.25,0.25,0,0,1-.22-0.13l-0.33-.6A3,3,0,0,1,16,10.19V8.75ZM6,5.85a2,2,0,0,1,4,0V7.28a6,6,0,0,1-.71,2.83L9,10.72a1,1,0,0,1-.88.53H7.92A1,1,0,0,1,7,10.72l-0.33-.61A6,6,0,0,1,6,7.28V5.85ZM14,19H2V17.25a2,2,0,0,1,1.26-1.86L7,13.92v-1a3,3,0,0,0,1,.18H8a3,3,0,0,0,1-.18v1l3.72,1.42A2,2,0,0,1,14,17.21V19Zm7,0H16V17.35a4,4,0,0,0-.55-2l1.05-.4V14.07a2,2,0,0,0,.4.05h0.2a2,2,0,0,0,.4-0.05v0.88l2.53,1a1.5,1.5,0,0,1,1,1.4V19Z"
                  class="fill-current"
                />
              </svg>
            </span>
            <p>My Network</p>
          </a>
        </div>
        <div class="flex-1 text-gray-400 text-xs border-b-2 border-transparent text-center -mb-2">
          <a href="#" class="block">
            <span class="inline-block -mb-1">
              <svg
                class="fill-current"
                viewBox="0 0 24 24"
                width="24px"
                height="24px"
                x="0"
                y="0"
                focusable="false"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M21,7H17V6a3,3,0,0,0-3-3H10A3,3,0,0,0,7,6V7H3A1,1,0,0,0,2,8V19a1,1,0,0,0,1,1H21a1,1,0,0,0,1-1V8A1,1,0,0,0,21,7ZM9,6a1,1,0,0,1,1-1h4a1,1,0,0,1,1,1V7H9V6ZM20,18H4V13H20v5Zm0-6H4V9H20v3Z"
                />
              </svg>
            </span>
            <p>Jobs</p>
          </a>
        </div>
        <div class="flex-1 text-gray-400 text-xs border-b-2 border-transparent text-center -mb-2">
          <a href="#" class="block">
            <span class="inline-block -mb-1">
              <svg
                class="fill-current"
                viewBox="0 0 24 24"
                width="24px"
                height="24px"
                x="0"
                y="0"
                focusable="false"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M21,8H8A1,1,0,0,0,7,9V19a1,1,0,0,0,1,1H18l4,3V9A1,1,0,0,0,21,8ZM20,19.11L18.52,18H9V10H20v9.11ZM12,15h5v1H12V15ZM4,13H5v2H3a1,1,0,0,1-1-1V4A1,1,0,0,1,3,3H16a1,1,0,0,1,1,1V6H15V5H4v8Zm14,0H11V12h7v1Z"
                />
              </svg>
            </span>
            <p>Messaging</p>
          </a>
        </div>
        <div class="flex-1 text-gray-400 text-xs border-b-2 border-transparent text-center -mb-2">
          <a href="#" class="block">
            <span class="inline-block -mb-1">
              <svg
                class="fill-current"
                viewBox="0 0 24 24"
                width="24px"
                height="24px"
                x="0"
                y="0"
                focusable="false"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M20.94,19L19,14.49s-0.41-3.06-.8-6.06A6.26,6.26,0,0,0,12,3h0A6.26,6.26,0,0,0,5.79,8.44L5,14.49,3.06,19a0.71,0.71,0,0,0-.06.28,0.75,0.75,0,0,0,.75.76H10a2,2,0,1,0,4,0h6.27A0.74,0.74,0,0,0,20.94,19ZM12,4.75h0a4.39,4.39,0,0,1,4.35,3.81c0.28,2.1.56,4.35,0.7,5.44H7L7.65,8.56A4.39,4.39,0,0,1,12,4.75ZM5.52,18l1.3-3H17.18l1.3,3h-13Z"
                />
              </svg>
            </span>

            <p>Notification</p>
          </a>
        </div>
        <div class="flex-1 text-gray-400 text-xs  text-center -mb-2">
          <a href="#" class="inline-block">
            <div class="-md-1">
              <img
                class="h-6 w-6 rounded-full"
                src="https://media.licdn.com/dms/image/C5603AQH13IPxsujwTQ/profile-displayphoto-shrink_100_100/0?e=1573689600&v=beta&t=pYBU1eoVB1aA5MBedhkOPA1UI9b_piyVFWW7ty6rBrw"
              />
            </div>
            <div class="flex items-center">
              <span class="inline-block">
                Me
                <svg
                  viewBox="0 0 24 24"
                  width="20px"
                  height="20px"
                  class="fill-current inline-block pt-1"
                  focusable="false"
                >
                  <path
                    d="M8.8,10.66L14,5.12A0.07,0.07,0,0,0,13.93,5H2.07A0.07,0.07,0,0,0,2,5.12L7.2,10.66A1.1,1.1,0,0,0,8.8,10.66Z"
                  />
                </svg>
              </span>
            </div>
          </a>
        </div>
        <div class="flex-1 text-gray-400 text-xs  border-gray-600 border-l text-center -mb-2">
          <a href="#" class="inline-block ">
            <span class="inline-block -mb-1">
              <svg
                viewBox="0 0 24 24"
                width="23px"
                height="23px"
                x="0"
                y="0"
               class="fill-current"
                focusable="false"
              >
                <path
                  d="M10,10h4v4H10V10Zm0,11h4V17H10v4ZM3,14H7V10H3v4Zm0,7H7V17H3v4ZM3,7H7V3H3V7Zm14,7h4V10H17v4ZM17,3V7h4V3H17ZM10,7h4V3H10V7Zm7,14h4V17H17v4Z"
               
                />
              </svg>
            </span>
            <div class="flex items-center">
              <span class="inline-block">
                Work
                <svg
                  viewBox="0 0 20 20"
                  width="20px"
                  height="20px"
                  class="fill-current inline-block pt-1"
                  focusable="false"
                >
                  <path
                    d="M8.8,10.66L14,5.12A0.07,0.07,0,0,0,13.93,5H2.07A0.07,0.07,0,0,0,2,5.12L7.2,10.66A1.1,1.1,0,0,0,8.8,10.66Z"
                  />
                </svg>
              </span>
            </div>
          </a>
        </div>
        <div class="px-6 text-yellow-200 text-xs border-b-2 border-transparent text-center -mb-2">
          <a href="#" class="hover:underline">
            <span>
              Upgrade to
              <br />Premium
            </span>
          </a>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
import Logo from "./Logo.vue";
export default {
  components: {
    Logo
  }
};
</script>

<style>
</style>