<!--
 * @Author: hzm
 * @Date: 2022-08-24 09:28:36
 * @Description: 
-->

<template>
  <div class="slidev-layout h-default">
    <div class="absolute left-0 top-0 transform rotate-90">
      <div class="relative">
        <svg
          width="322"
          height="279"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          class="absolute bottom-0"
        >
          <path
            d="M92.5 38C73.3 18.8 22.833 4.667 0 0v278.5h322c-5.167-9.333-23.6-30-56-38-40.5-10-78.5-26.5-90-38.5s-32-44-39-79-20.5-61-44.5-85Z"
            fill="#6EE7B7"
            fill-opacity="30"
          ></path></svg
        ><svg
          width="317"
          height="83"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          class="absolute bottom-0 left-40 opacity-40"
        >
          <path
            d="M6.095 82.907c-2.434.194-4.475.175-6.095 0h6.095c16.096-1.282 49.361-11.864 91.405-48 60.5-52 137-53.5 219.5 48H6.095Z"
            fill="#E3F9B4"
          ></path>
        </svg>
      </div>
    </div>
    <slot />
    <svg
      width="261"
      height="158"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
      class="absolute top-20 -right-30"
    >
      <path
        d="M3 23 28.5 3 54 23 79.5 3 105 23l25.5-20L156 23l25.5-20L207 23l25.5-20L258 23M3 67l25.5-20L54 67l25.5-20L105 67l25.5-20L156 67l25.5-20L207 67l25.5-20L258 67M3 111l25.5-20L54 111l25.5-20 25.5 20 25.5-20 25.5 20 25.5-20 25.5 20 25.5-20 25.5 20M3 155l25.5-20L54 155l25.5-20 25.5 20 25.5-20 25.5 20 25.5-20 25.5 20 25.5-20 25.5 20"
        stroke="#808996"
        stroke-opacity="30"
        stroke-width="6"
        stroke-linecap="round"
        stroke-linejoin="round"
      ></path>
    </svg>
  </div>
</template>