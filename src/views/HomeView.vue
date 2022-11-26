<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <iframe
      src="https://gateway.ipfscdn.io/ipfs/Qmcine1gpZUbQ73nk7ZGCcjKBVFYXrEtqrhujXk3HDQ6Nn/erc721.html?contract=0x5294f4Ccaf54e65b9ACE6FA40B11A34791c1EEF7&chainId=137&theme=dark"
      width="600px"
      height="600px"
      style="max-width: 100%"
      frameborder="0"
    ></iframe>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>
