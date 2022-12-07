<template>
  <div id="app">
    <header>
      <div class="time-contacts-container">
        <div class="time"></div>
        <div class="contacts"></div>
      </div>

      <div class="logo-menu-container">
        <div class="logo">logo</div>

        <div class="menu-button">
          <MenuC :pages="pages" />
          <div>1</div>
          <div>2</div>
          <button class="pill-btn light-acqua-btn">BUY NEXGEN</button>
        </div>
      </div>
    </header>

    <main>
      <section class="fusions-acquisitions">
        <div class="fusion-right">
          <!-- farlo quadrato con dentro gli elementi H input group e btn stondato flex-end oppure dentro un div flexato end -->
          <h4>FUSIONS & ACQUISITIONS</h4>
          <h2>
            Insurance <br />
            Consulting
          </h2>
          <div class="input-group">
            <!-- div da flexare e wrappare 2 campi w40 del tot del quadrato flexato a dx -->
            <input type="text" placeholder="Name" />
            <input type="text" placeholder="Email" />
            <input type="text" placeholder="Phone" />
            <select name="services" id="">
              <option value="">---</option>
              <option value="">Sales and Purchasing</option>
              <option value="">Financial and Accounts</option>
              <option value="">Human Resources</option>
              <option value="">Another Subject</option>
            </select>
          </div>
          <button class="acqua-btn pill-btn">SEND</button>
        </div>
      </section>

      <section class="about">
        <div class="company-dark">
          <!-- flex 2 "quadrati" con piu spazio a dx che a sx -->
          <div class="company-left">
            <h4>ABOUT THE NETWORK</h4>
            <h2>The Company</h2>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Sed
              fugiat numquam accusamus nesciunt neque dolorum saepe, ratione
              earum, deleniti vero in enim porro illo inventore excepturi.
              Deserunt, illum? Dicta, optio!
            </p>
          </div>
          <div class="company-right">
            <!-- flexato wrappato con i div interni larghi 40% (misure come sull'header per campi di input) -->
            <div class="company-values">
              <h3>Tradition ecc.</h3>
              <p>lorem ipsum dolor sit amet conserctun adispifbn elit.</p>
            </div>
            <div class="company-values">
              <h3>Tradition ecc.</h3>
              <p>lorem ipsum dolor sit amet conserctun adispifbn elit.</p>
            </div>
            <div class="company-values">
              <h3>Tradition ecc.</h3>
              <p>lorem ipsum dolor sit amet conserctun adispifbn elit.</p>
            </div>
            <div class="company-values">
              <h3>Tradition ecc.</h3>
              <p>lorem ipsum dolor sit amet conserctun adispifbn elit.</p>
            </div>
          </div>
        </div>
        <div class="excellence light-gray">
          <div class="excellence-heading justify-between align-center flex">
            <!-- flexato e space between -->
            <div>
              <h2>Excellence in Services</h2>
              <p>
                We are leaders in providing consultancy servicer with a set of
                cutting edge technologies and term of experienced and renowed
                professionald. These are some options that you van hire.
              </p>
            </div>
            <button class="pill-btn acqua-btn">SEE ALL</button>
          </div>
          <div class="service-cards-container flex flex-wrap justify-between">
            <!-- flexato e wrappato x3 -->
            <div class="service-card">
              <div class="my-1">IC</div>
              <h3 class="my-1">Audit & Assurance</h3>
              <p class="my-1">
                Lorem ipsum dolor sirt smrt cojnsecuroe adsicping elit.
              </p>
              <button class="pill-btn acqua-btn my-1">Read More</button>
            </div>
            <div class="service-card">
              <div class="my-1">IC</div>
              <h3 class="my-1">Audit & Assurance</h3>
              <p class="my-1">
                Lorem ipsum dolor sirt smrt cojnsecuroe adsicping elit.
              </p>
              <button class="pill-btn acqua-btn my-1">Read More</button>
            </div>
            <div class="service-card">
              <div class="my-1">IC</div>
              <h3 class="my-1">Audit & Assurance</h3>
              <p class="my-1">
                Lorem ipsum dolor sirt smrt cojnsecuroe adsicping elit.
              </p>
              <button class="pill-btn acqua-btn my-1">Read More</button>
            </div>
            <div class="service-card">
              <div class="my-1">IC</div>
              <h3 class="my-1">Audit & Assurance</h3>
              <p class="my-1">
                Lorem ipsum dolor sirt smrt cojnsecuroe adsicping elit.
              </p>
              <button class="pill-btn acqua-btn my-1">Read More</button>
            </div>
            <div class="service-card">
              <div class="my-1">IC</div>
              <h3 class="my-1">Audit & Assurance</h3>
              <p class="my-1">
                Lorem ipsum dolor sirt smrt cojnsecuroe adsicping elit.
              </p>
              <button class="pill-btn acqua-btn my-1">Read More</button>
            </div>
            <div class="service-card">
              <div class="my-1">IC</div>
              <h3 class="my-1">Audit & Assurance</h3>
              <p class="my-1">
                Lorem ipsum dolor sirt smrt cojnsecuroe adsicping elit.
              </p>
              <button class="pill-btn acqua-btn my-1">Read More</button>
            </div>
          </div>
        </div>
      </section>

      <section class="how-it-works">
        <div class="thick-how-it-works">
          <h4>HOW IT WORKS IN PRACTICE</h4>
          <h2>Process Management</h2>
          <p>
            We work wirh inoobstive methosologies to endurte that rthe ebtire
            refitmarring provesdds is domenfrom start to finish as planned
          </p>
        </div>
        <div class="acqua-line">
          <div class="largo100 flex">
            <div class="process-step-card">
              <div class="acqua-square">01</div>
              <h3>Information</h3>
              <p>Lorem ipsum dolor uir amer conseutreo adicpisng</p>
            </div>
            <div class="process-step-card">
              <div class="acqua-square">02</div>
              <h3>Planning</h3>
              <p>Lorem ipsum dolor uir amer conseutreo adicpisng</p>
            </div>
            <div class="process-step-card">
              <div class="acqua-square">03</div>
              <h3>Assignment</h3>
              <p>Lorem ipsum dolor uir amer conseutreo adicpisng</p>
            </div>
            <div class="process-step-card">
              <div class="acqua-square">04</div>
              <h3>Formatting</h3>
              <p>Lorem ipsum dolor uir amer conseutreo adicpisng</p>
            </div>
            <div class="process-step-card">
              <div class="acqua-square">05</div>
              <h3>Continuity</h3>
              <p>Lorem ipsum dolor uir amer conseutreo adicpisng</p>
            </div>
          </div>
        </div>
      </section>

      <section class="team">
        <h4>WE LIKE WHAT WE DO</h4>
        <h2>Team of Experts</h2>
        <div class="contenitore-team">
          <!-- VUE CARD COMPONENT PERSONE -->
        </div>
      </section>

      <section class="logistics-solutions light">
        <h4>LOGISTIC SOLUTIONS</h4>
        <h2>Structured Warehouse</h2>
        <p>
          We develop operational strategies with cuittomers to improve
          logistical efficiency.
        </p>
        <div class="gallery flex flex-wrap justify-between">
          <div class="pic-component">
            <img src="./../public/img/news-1.jpg" alt="" />
          </div>
          <div class="pic-component">
            <img src="./../public/img/news-2.jpg" alt="" />
          </div>
          <div class="pic-component">
            <img src="./../public/img/news-3.jpg" alt="" />
          </div>
          <div class="pic-component">
            <img src="./../public/img/news-4.jpg" alt="" />
          </div>
          <div class="pic-component">
            <img src="./../public/img/news-5.jpg" alt="" />
          </div>
          <div class="pic-component">
            <img src="./../public/img/news-2.jpg" alt="" />
          </div>
        </div>
      </section>

      <section class="newsletter flex align-center justify-between">
        <div class="newsletter-left">
          <h4>NEWSLETTER</h4>
          <h2>Know First</h2>
          <p>
            Follow closely and recrive newa of the current market. By submitting
            the fotm you agree to the
            <span class="acqua-text">terms of use</span>.
          </p>
        </div>
        <div class="newsletter-right flex flex-wrap">
          <input type="text" placeholder="Name" />
          <input type="text" placeholder="Email" />
          <button class="pill-btn acqua-btn">SUBSCRIBE</button>
          <div class="send-confirmation-messsage">
            <div>
              <!-- vif no bordo 2px solid rosso-->
            </div>
            <div>
              <!-- velse si bor. 2 px verde-->
            </div>
          </div>
        </div>
      </section>
    </main>

    <footer class="flex justify-between">
      <div class="nexgen-info footer-card">
        <div class="my-2">Logo</div>
        <p>build the smallest detail with a focus on feature availability.</p>
        <div class="my-1">
          <span>IC</span>
          <span> +1 3347-343</span>
        </div>
        <div class="my-1">
          <span>IC</span>
          <span> +1 3347-343</span>
        </div>
        <div class="my-1">
          <span>IC</span>
          <span> +1 3347-343</span>
        </div>
        <button class="light-acqua-btn pill-btn my-2">BUY NEXGEN</button>
      </div>

      <div
        v-for="(elem, index) in pages"
        :key="index"
        class="footer-card footer-card-dark"
      >
        <h3 class="page-item-menu">{{ elem.name }}</h3>
        <ul class="sub-pages-footer-menu">
          <li v-for="(el, index) in elem.sub_pages" :key="index">
            <div class="page-item-menu">{{ el.name }}</div>
            <ul>
              <li v-for="(e, index) in el.sub_sub_pages" :key="index">
                <div class="page-item-menu">{{ e.name }}</div>
              </li>
            </ul>
          </li>
        </ul>
      </div>

      <div class="foot"></div>
    </footer>
  </div>
</template>

<script>
import MenuC from "./components/MenuC.vue";

export default {
  name: "App",
  components: {
    MenuC,
  },
  data() {
    return {
      pages: [
        {
          name: "Page 1",
          link: "",
          // secondo livello di profondità
          sub_pages: [
            {
              name: "sub1",
              link: "",
              sub_sub_pages: [],
            },
            {
              name: "sub2",
              link: "",
              // terzo livello di profondità
              sub_sub_pages: [
                {
                  name: "sub-sub1",
                  link: "",
                },
                {
                  name: "sub-sub2",
                  link: "",
                },
              ],
            },
          ],
        },
        {
          name: "Page 2",
          link: "",
          sub_pages: [
            {
              name: "sub1",
              link: "",
              sub_sub_pages: [],
            },
            {
              name: "sub2",
              link: "",
              sub_sub_pages: [],
            },
          ],
        },
        {
          name: "Page 3",
          link: "",
          sub_pages: [
            {
              name: "sub1",
              link: "",
              sub_sub_pages: [
                {
                  name: "sub-sub1",
                  link: "",
                },
                {
                  name: "sub-sub2",
                  link: "",
                },
              ],
            },
            {
              name: "sub2",
              link: "",
              sub_sub_pages: [],
            },
          ],
        },
        {
          name: "Page 4",
          link: "",
          sub_pages: [
            {
              name: "sub1",
              link: "",
              sub_sub_pages: [],
            },
            {
              name: "sub2",
              link: "",
              sub_sub_pages: [],
            },
          ],
        },
        {
          name: "Shop",
          link: "",
          sub_pages: [],
        },
      ],
    };
  },
  methods: {},
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Work+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

@import "./assets/utility.scss";

// @import "./assets/utility2.scss";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  height: 200vh;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

h2 {
  font-size: 3rem;
  font-weight: 900;
  color: #3d4955;
}

h3 {
  font-size: 1.5rem;
}

h4 {
  color: #45bbbc;
}

.pill-btn {
  border-radius: 2rem;
  padding: 0.6rem 1.2rem;
  border: none;
  font-size: 1rem;
  cursor: pointer;
  color: white;
}

.light-acqua-btn {
  background-color: rgba(255, 255, 255, 0.2);
}

.light-acqua-btn:hover {
  background-color: rgba(255, 255, 255, 0.8);
  transition: all 1s;
  color: #048383;
  font-weight: 900;
}

.acqua-btn {
  background-color: #048383;
}

.acqua-btn:hover {
  transform: scaleX(1.1);
  transition: all 1s;
}

header {
  background-image: linear-gradient(90deg, #111117, #1d4963 75%);
  position: fixed;
  width: 100%;
  z-index: 1;
}

.logo-menu-container {
  width: 80%;
  height: 10vh;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  text-align: center;
  color: #aeb0b0;
  font-weight: 700;
}

.menu-button {
  width: 65%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.fusions-acquisitions {
  height: 100vh;
  width: 100%;
  display: flex;
  justify-content: end;
  background-image: url(./../public/img/bg-6.jpg);
  background-size: cover;
  padding-top: 15%;
  padding-right: 10%;
}

.fusion-right {
  width: 45%;
}

.input-group {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin-bottom: 1rem;

  input,
  select {
    width: 48%;
    height: 3rem;
    margin: 0.5rem 0;
    background-color: lightgray;
    border: none;
    padding: 1.2rem;
    font-family: Helvetica, sans-serif;
    font-weight: 700;
  }
}

// ABOUT

.company-dark {
  width: 100%;
  display: flex;
  background-image: linear-gradient(90deg, #111117, #22343e 85%);
  padding: 10%;

  h2,
  h3 {
    color: white;
  }
  p {
    color: lightgray;
  }
}

.company-right {
  width: 45%;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
}

.company-values {
  width: 48%;
}

.company-left {
  width: 47%;
  margin-right: 2rem;
}

// EXCELLENCE

.excellence {
  padding: 5% 10%;
  background-color: #e8ecea;
}

.excellence-heading {
  div {
    width: 70%;
  }
}

.service-cards-container {
  margin: 1rem 0;
}

.service-card {
  width: 30%;
  padding: 2rem;
  background-color: white;
  border-radius: 0.5rem;
  margin: 1.6rem 0;
}

.how-it-works {
  padding-top: 5%;
  padding-bottom: 12%;
}

.thick-how-it-works {
  width: 60%;
  margin: auto;
  text-align: center;
}

.acqua-line {
  width: 100%;
  height: 0.5rem;
  background-color: #c8ebeb;
  position: relative;
  margin: 5rem 0;
}

.largo100 {
  width: 100%;
  position: absolute;
  top: -600%;
  display: flex;
  justify-content: center;
}

.process-step-card {
  width: 12%;
  margin: 0 2rem;
  text-align: center;
}

.acqua-square {
  width: 40%;
  margin: 1rem auto;
  aspect-ratio: 1/1;
  background-color: #c8ebeb;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 0.4rem;
  color: #078282;
  font-size: 2rem;
  font-weight: 900;
}

.team {
  padding: 5% 10%;
  background-image: linear-gradient(90deg, #111117, #22343e 85%);
  text-align: center;
  h2 {
    color: white;
  }
}

.logistics-solutions {
  padding: 5% 10%;
  text-align: center;
}

.gallery {
  width: 100%;
  margin: 0 0 0 0;
}

.pic-component {
  width: 30%;
  margin: 1.6rem 0;

  img {
    width: 100%;
  }
}

.newsletter {
  background-image: url(./../public/img/bg-1.jpg);
  padding: 10% 10%;
  width: 100%;
  margin: auto;
  h2 {
    color: white;
  }
  p {
    color: lightgray;
  }

  .newsletter-left {
    width: 40%;
  }

  .newsletter-right {
    width: 50%;

    input {
      width: 100%;
      height: 3rem;
      margin: 0.5rem 0;
      background-color: lightgray;
      border: none;
      padding: 1.2rem;
      font-family: Helvetica, sans-serif;
      font-weight: 700;
    }

    button {
      margin-bottom: 1rem;
    }
  }
}

footer {
  padding: 5% 10%;
  background-image: linear-gradient(90deg, #111117, #22343e 85%);
  color: lightgray;

  .footer-card {
    width: calc(90% / 6);
    border-radius: 0.8rem;
    padding: 1rem;

    h3 {
      text-transform: uppercase;
    }

    ul {
      list-style: none;
      text-transform: uppercase;
    }

    li {
      margin: 1rem 0;
      font-weight: 700;
    }

    .sub-pages-footer-menu {
      margin-top: 3rem;
    }
  }

  .page-item-menu:hover {
    color: #048383;
    cursor: pointer;
    transition: all 0.5s;
  }

  .footer-card-dark {
    background-color: rgba(17, 17, 23, 0.5);
  }

  .footer-card-dark:hover {
    top: -10px;
    transition: all 1s ease-out;
  }
}

.nexgen-info {
}
</style>
