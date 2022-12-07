<template>
  <div class="def dropdown flex flex-column">
    <ul class="tutta-la-lista">
      <li>
        {{ pageObj.name }}
      </li>
      <li>
        <ul class="dropdown-content">
          <li
            v-for="(elem, index) in pageObj.sub_pages"
            :key="index"
            class="dropdown2 flex relative"
          >
            <div>{{ elem.name }}</div>
            <ul class="sub-sub-pages-list">
              <li v-for="(el, index) in elem.sub_sub_pages" :key="index">
                {{ el.name }}
              </li>
            </ul>
          </li>
        </ul>
      </li>
    </ul>
    <div></div>
  </div>
</template>

<script>
export default {
  name: "PageC",
  components: {},
  props: {
    pageObj: Object,
  },
  data() {
    return {};
  },
  methods: {},
};
</script>

<style lang="scss" scoped>
.def {
  text-align: center;
}

ul {
  list-style: none;
}

.dropdown {
  position: relative;
  display: inline-block;
  cursor: pointer;
}

.dropdown-content {
  display: none;
  position: absolute;
  width: 100%;
  top: 100%;
  background-color: #f9f9f9;
  text-align: center;

  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;

  .debug {
    display: none;
  }

  li {
    list-style: none;
    display: block;
    padding: 5% 0;
    border-left: 4px solid #f9f9f9;
    cursor: pointer;
  }

  li:hover {
    border-left: 4px solid #048383;
    transition: all 0.3s;
  }
}

.dropdown:hover .dropdown-content {
  display: block;
}

.debug {
  position: absolute;
  left: 100%;
}

.sub-sub-pages-list {
  display: none;
  position: absolute;
  left: 100%;
  top: 0;
  background-color: #f9f9f9;
  width: 100%;
}

.dropdown2:hover .sub-sub-pages-list {
  display: block;
}
</style>