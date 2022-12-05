<template>
  <div id="app">
    <header>
      <div class="time-contacts-container">
        <div class="time"></div>
        <div class="contacts"></div>
      </div>
      <div class="logo-menu-container">
        <div class="logo">logo</div>
        <div>
          <!-- VUE COMPONENT MENU WITH SUB-MENUS -->
        </div>
      </div>
      <div class="quadrato-fusions-acquisitions">
        <!-- farlo quadrato con dentro gli elementi H input group e btn stondatoflex-end oppure dentro un div flexato end -->
        <h4>FUSIONS AND ACQUISITIONS</h4>
        <h2>Insurance Consulting</h2>
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
          <button>SEND</button>
          <div class="send-confirmation-messsage">
            <div>
              <!-- vif no bordo 2px solid rosso-->
            </div>
            <div>
              <!-- velse si bor. 2 px verde-->
            </div>
          </div>
        </div>
      </div>
    </header>

    <main>
      <section class="about">
        <div class="company dark">
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
            <div>
              <span>
                IC
                <h3>Tradition ecc.</h3>
              </span>
              <p>lorem ipsum dolor sit amet conserctun adispifbn elit.</p>
            </div>
            <div>
              <span>
                IC
                <h3>Tradition ecc.</h3>
              </span>
              <p>lorem ipsum dolor sit amet conserctun adispifbn elit.</p>
            </div>
            <div>
              <span>
                IC
                <h3>Tradition ecc.</h3>
              </span>
              <p>lorem ipsum dolor sit amet conserctun adispifbn elit.</p>
            </div>
            <div>
              <span>
                IC
                <h3>Tradition ecc.</h3>
              </span>
              <p>lorem ipsum dolor sit amet conserctun adispifbn elit.</p>
            </div>
          </div>
        </div>
        <div class="excellence light-gray">
          <div>
            <!-- flexato e space between -->
            <div>
              <h2>Excellence in Services</h2>
              <p>
                We are leaders in providing consultancy servicer with a set of
                cutting edge technologies and term of experienced and renowed
                professionald. These are some options that you van hire
              </p>
            </div>
            <button>SEE ALL</button>
          </div>
          <div class="service-cards-container">
            <!-- flexato e wrappato x3 -->
            <div class="service-card">
              <!-- (potenziale COMPONENT)tot/3 piu spazi. il clic vale su tutta la card il btn non serve basta stilizzare un div come btn precedenti-->
              <div>IC</div>
              <h3>Audit & Assurance</h3>
              <p>Lorem ipsum dolor sirt smrt cojnsecuroe adsicping elit.</p>
              <button>Read More</button>
            </div>
          </div>
        </div>
      </section>

      <section class="how-it-works light">
        <div class="stretto">
          <h4>HOW IT WORKS IN PRACTICE</h4>
          <h2>Process Management</h2>
          <p>
            We work wirh inoobstive methosologies to endurte that rthe ebtire
            refitmarring provesdds is domenfrom start to finish as planned
          </p>
        </div>
        <div class="largo100">
          <!-- position relative -->
          <div>linea verde in position absolute</div>
          <div class="largo100">
            <!-- position absolute anche lui con dentro i numeri  -->
          </div>
        </div>
      </section>
      <section class="what-we-do">
        <h2></h2>
        <div class="contenitore-team">
          <!-- VUE CARD COMPONENT PERSONE -->
        </div>
      </section>
      <section class="logistics-solutions">
        <div class="heading"></div>
        <div class="gallery">
          <!-- VUE CARD COMPONENT FOTO -->
        </div>
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
