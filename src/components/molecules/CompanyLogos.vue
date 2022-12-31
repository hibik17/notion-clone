<template>
  <div v-for="(logo, index) in companyLogoArray" :key="index">
    <CompanyLogo :logo="logo" />
  </div>
</template>

<script setup lang="ts">
import CompanyLogo from "../atoms/companyLogo.vue";

const companyLogoArray = [
  "https://images.ctfassets.net/spoqsaf9291f/37B7qVI9fp06fAJU1ixRim/41a0d5f4c8d867e86c08c5defc6c26f3/mitsubishi-logo.png",
  "https://images.ctfassets.net/spoqsaf9291f/5XG3oCJz5XCLKfPPrk3N5w/b55f3cabea3d372468520cf181cef970/suntory.png",
  "https://images.ctfassets.net/spoqsaf9291f/4GE2GXalijSE3wzD3TOiZe/48f5ac098fb6da656f4e8e0710162dcb/slv_logo_2__1_.png",
  "https://images.ctfassets.net/spoqsaf9291f/Zs8RTKZRItl191yfF0ws0/fce9876650c7ac6439eebffd9db9d941/Smartnews__1_.png",
  "https://images.ctfassets.net/spoqsaf9291f/1T707N4jLD5xkQXP0I8WaJ/28b78d63b3f48a60fda95cb0dd145166/raksul-logo.png",
];
</script>
