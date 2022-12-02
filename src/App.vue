<template>
  <div id="app">
    <header>
      <div class="time-contacts-container">
        <div class="time"></div>
        <div class="contacts"></div>
      </div>
      <div class="logo-menu-container">
        <div class="logo">logo</div>
        <div>VUE COMPONENT MENU WITH SUB-MENUS</div>
      </div>
      <div class="quadrato-fusions-acquisitions">
        <!-- farlo quadrato con dentro gli elementi H input group e btn stondatoflex-end oppure dentro un div flexato end -->
      </div>
    </header>
    <main>
      <section class="about">
        <div class="dark"></div>
        <div class="light-gray"></div>
      </section>
      <section class="how-it-works">
        <div class="stretto"></div>
        <div class="largo100">numeri</div>
      </section>
      <section class="what-we-do">
        <h2></h2>
        <div class="contenitore-team">VUE CARD COMPONENT PERSONE</div>
      </section>
      <section class="logistics-solutions">
        <div class="heading"></div>
        <div class="gallery">VUE CARD COMPONENT FOTO</div>
      </section>
      <section class="newsletter"></section>
    </main>
    <footer>
      <div class="principale"></div>
      <div class="foot"></div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  height: 200vh;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
