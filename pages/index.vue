<template>
  <div>
    <h1>HOME</h1>
    <section data-scroll-section>
      <div>
        <Logo data-scroll data-scroll-speed="1" :width="350" />
        <h1 class="title">
          NUXT
          <span class="green">JS</span>
        </h1>
        <h2 class="subtitle">Starter for CodeSandBox</h2>
        <div class="links">
          <a href="https://nuxtjs.org/" target="_blank" class="button--green"
            >Documentation
            <IconLink />
          </a>
          <NLink to="/about" class="button--grey">About</NLink>
        </div>
      </div>
    </section>
    <section data-scroll-section>
      <div>
        <Logo data-scroll data-scroll-speed="1" :width="350" />
        <h1 class="title">
          NUXT
          <span class="green">JS</span>
        </h1>
        <h2 class="subtitle">Starter for CodeSandBox</h2>
        <div class="links">
          <a href="https://nuxtjs.org/" target="_blank" class="button--green"
            >Documentation
            <IconLink />
          </a>
          <NLink to="/about" class="button--grey">About</NLink>
        </div>
      </div>
    </section>
    <section data-scroll-section data-scroll-call="hello">
      <div>
        <Logo data-scroll data-scroll-speed="1" :width="350" />
        <h1 class="title">
          NUXT
          <span class="green">JS</span>
        </h1>
        <h2 class="subtitle">Starter for CodeSandBox</h2>
        <div class="links">
          <a href="https://nuxtjs.org/" target="_blank" class="button--green"
            >Documentation
            <IconLink />
          </a>
          <NLink to="/about" class="button--grey">About</NLink>
        </div>
      </div>
    </section>
    <section data-scroll-section>
      <div>
        <Logo :width="350" />
        <h1 class="title">
          NUXT
          <span class="green">JS</span>
        </h1>
        <h2 class="subtitle">Starter for CodeSandBox</h2>
        <div class="links">
          <a href="https://nuxtjs.org/" target="_blank" class="button--green"
            >Documentation
            <IconLink />
          </a>
          <NLink to="/about" class="button--grey">About</NLink>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";
import IconLink from "~/components/IconLink.vue";
import locomotive from "~/mixins/locomotive.js";

export default {
  components: {
    Logo,
    IconLink,
  },
  methods: {
    hello: function () {
      console.log("hey");
    },
  },
  mixins: [locomotive],
  mounted() {
    // hello () => console.log("hey");
  },
};
</script>

<style scoped>
.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 400;
  font-size: 100px;
  color: #2e495e;
  letter-spacing: 1px;
  font-size: 6em;
}
.green {
  color: #00c48d;
}

.subtitle {
  font-weight: 300;
  font-size: 3em;
  color: #2e495e;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
