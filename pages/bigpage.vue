<template>
  <div>
    <h1>ABOUT</h1>
    <section data-scroll-section>
      <div>
        <Logo data-scroll data-scroll-speed="1" :width="350"/>
        <h1 class="title">
          NUXT
          <span class="green">JS</span>
        </h1>
        <h2 class="subtitle">Starter for CodeSandBox</h2>
        <div class="links">
          <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation
            <IconLink/>
          </a>
          <NLink to="/about" class="button--grey">About</NLink>
        </div>
      </div>
    </section>
    <section data-scroll-section>
      <div>
        <Logo data-scroll data-scroll-speed="1" :width="350"/>
        <h1 class="title">
          NUXT
          <span class="green">JS</span>
        </h1>
        <h2 class="subtitle">Starter for CodeSandBox</h2>
        <div class="links">
          <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation
            <IconLink/>
          </a>
          <NLink to="/about" class="button--grey">About</NLink>
        </div>
      </div>
    </section>
    <section data-scroll-section>
      <div>
        <Logo data-scroll data-scroll-speed="1" :width="350"/>
        <h1 class="title">
          NUXT
          <span class="green">JS</span>
        </h1>
        <h2 class="subtitle">Starter for CodeSandBox</h2>
        <div class="links">
          <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation
            <IconLink/>
          </a>
          <NLink to="/about" class="button--grey">About</NLink>
        </div>
      </div>
    </section>
    <section data-scroll-section>
      <div>
        <Logo :width="350"/>
        <h1 class="title">
          NUXT
          <span class="green">JS</span>
        </h1>
        <h2 class="subtitle">Starter for CodeSandBox</h2>
        <div class="links">
          <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation
            <IconLink/>
          </a>
          <NLink to="/about" class="button--grey">About</NLink>
        </div>
      </div>
    </section>
        <section data-scroll-section>
      <div>
        <Logo :width="350"/>
        <h1 class="title">
          NUXT
          <span class="green">JS</span>
        </h1>
        <h2 class="subtitle">Starter for CodeSandBox</h2>
        <div class="links">
          <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation
            <IconLink/>
          </a>
          <NLink to="/about" class="button--grey">About</NLink>
        </div>
      </div>
    </section>
        <section data-scroll-section>
      <div>
        <Logo :width="350"/>
        <h1 class="title">
          NUXT
          <span class="green">JS</span>
        </h1>
        <h2 class="subtitle">Starter for CodeSandBox</h2>
        <div class="links">
          <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation
            <IconLink/>
          </a>
          <NLink to="/about" class="button--grey">About</NLink>
        </div>
      </div>
    </section>
        <section data-scroll-section>
      <div>
        <Logo :width="350"/>
        <h1 class="title">
          NUXT
          <span class="green">JS</span>
        </h1>
        <h2 class="subtitle">Starter for CodeSandBox</h2>
        <div class="links">
          <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation
            <IconLink/>
          </a>
          <NLink to="/about" class="button--grey">About</NLink>
        </div>
      </div>
    </section>
        <section data-scroll-section>
      <div>
        <Logo :width="350"/>
        <h1 class="title">
          NUXT
          <span class="green">JS</span>
        </h1>
        <h2 class="subtitle">Starter for CodeSandBox</h2>
        <div class="links">
          <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation
            <IconLink/>
          </a>
          <NLink to="/about" class="button--grey">About</NLink>
        </div>
      </div>
    </section>
        <section data-scroll-section>
      <div>
        <Logo :width="350"/>
        <h1 class="title">
          NUXT
          <span class="green">JS</span>
        </h1>
        <h2 class="subtitle">Starter for CodeSandBox</h2>
        <div class="links">
          <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation
            <IconLink/>
          </a>
          <NLink to="/about" class="button--grey">About</NLink>
        </div>
      </div>
    </section>
        <section data-scroll-section>
      <div>
        <Logo :width="350"/>
        <h1 class="title">
          NUXT
          <span class="green">JS</span>
        </h1>
        <h2 class="subtitle">Starter for CodeSandBox</h2>
        <div class="links">
          <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation
            <IconLink/>
          </a>
          <NLink to="/about" class="button--grey">About</NLink>
        </div>
      </div>
    </section>
        <section data-scroll-section>
      <div>
        <Logo :width="350"/>
        <h1 class="title">
          NUXT
          <span class="green">JS</span>
        </h1>
        <h2 class="subtitle">Starter for CodeSandBox</h2>
        <div class="links">
          <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation
            <IconLink/>
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
    IconLink
  },
  mixins: [locomotive]
};
</script>

<style scoped>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
h1 {
  font-weight: 400;
}
.name {
  color: #00C48D;
}
p {
  margin-top: 20px;
}
</style>
