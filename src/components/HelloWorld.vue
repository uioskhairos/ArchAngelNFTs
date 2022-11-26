<template>
  <div class="hello">
    <!-- <h1>{{ msg }}</h1> -->
    <div>
      <img
        alt="Vue logo"
        src="../assets/banner.png"
        height="10%"
        width="100%"
      />
    </div>
    <h3>Essential Links</h3>
    <ul>
      <li>
        <a href="/" rel="noopener">Core Docs</a>
      </li>
      <li>
        <a
          href="https://opensea.io/collection/archangel-nfts"
          target="_blank"
          rel="noopener"
          >Opensea
        </a>
      </li>
      <li>
        <a href="https://discord.gg/2RGkyuTM7V" target="_blank" rel="noopener"
          >Discord
        </a>
      </li>
      <li>
        <a
          href="https://twitter.com/NftArchangels"
          target="_blank"
          rel="noopener"
          >Twitter
        </a>
      </li>
      <li>
        <a
          href="https://www.facebook.com/ArchAngelNFT"
          target="_blank"
          rel="noopener"
          >Facebook
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #7355f8;
}
</style>
