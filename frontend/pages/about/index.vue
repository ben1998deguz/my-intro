<template>
  <div class="about">
    <div class="parallaxAbout" />
    <mdb-jumbotron class="cardHeight mb-0 text-center">
      <h2 class="card-title h2">
        {{ $t('name') }}
      </h2>
      <p class="indigo-text my-4 font-weight-bold">
        {{ $t('free') }}
      </p>
      <mdb-row class="d-flex justify-content-center">
        <mdb-col xl="7" class="pb-2">
          <p class="card-text">
            {{ $t('aboutIntro') }}
          </p>
        </mdb-col>
      </mdb-row>
    </mdb-jumbotron>

    <mdb-container>
      <mdb-container class="max">
        <section class="my-5">
          <h2 class="h1-responsive font-weight-bold text-center my-5">
            {{ $t('skills') }}
          </h2>
          <mdb-row>
            <mdb-col lg="5" class="text-center text-lg-left">
              <img class="img-fluid" src="~assets/images/screens-section.jpg" alt="Sample image">
            </mdb-col>
            <mdb-col lg="7">
              <mdb-row class="mb-3">
                <mdb-col size="1">
                  <mdb-icon icon="share" size="lg" class="mb-3 mt-3" />
                </mdb-col>
                <mdb-col xl="10" md="11" size="10">
                  <h5 class="font-weight-bold mb-3">
                    HTML5/CSS3/JavaScript (ES6, ES7, ES8, ES9)
                  </h5>
                </mdb-col>
              </mdb-row>
              <mdb-row class="mb-3">
                <mdb-col size="1">
                  <mdb-icon icon="share" size="lg" class="mb-3 mt-3" />
                </mdb-col>
                <mdb-col xl="10" md="11" size="10">
                  <h5 class="font-weight-bold mb-3">
                    CSS Prepocessors: LESS, SASS, SCSS
                  </h5>
                </mdb-col>
              </mdb-row>
              <mdb-row class="mb-3">
                <mdb-col size="1">
                  <mdb-icon icon="share" size="lg" class="mb-3 mt-3" />
                </mdb-col>
                <mdb-col xl="10" md="11" size="10">
                  <h5 class="font-weight-bold mb-3">
                    JS Frameworks: Vue.js, Nuxt.js, React.js
                  </h5>
                </mdb-col>
              </mdb-row>
              <mdb-row class="mb-3">
                <mdb-col size="1">
                  <mdb-icon icon="share" size="lg" class="mb-3 mt-3" />
                </mdb-col>
                <mdb-col xl="10" md="11" size="10">
                  <h5 class="font-weight-bold mb-3">
                    CSS Frameworks: Bootstrap/Bootstrap-Vue, Vuetify.js, Vuesax
                  </h5>
                </mdb-col>
              </mdb-row>
              <mdb-row class="mb-3">
                <mdb-col size="1">
                  <mdb-icon icon="share" size="lg" class="mb-3 mt-3" />
                </mdb-col>
                <mdb-col xl="10" md="11" size="10">
                  <h5 class="font-weight-bold mb-3">
                    {{ $t('methodology') }}
                  </h5>
                </mdb-col>
              </mdb-row>
              <mdb-row class="mb-3">
                <mdb-col size="1">
                  <mdb-icon icon="share" size="lg" class="mb-3 mt-3" />
                </mdb-col>
                <mdb-col xl="10" md="11" size="10">
                  <h5 class="font-weight-bold mb-3">
                    {{ $t('agilep') }}
                  </h5>
                </mdb-col>
              </mdb-row>
              <mdb-row class="mb-3">
                <mdb-col size="1">
                  <mdb-icon icon="share" size="lg" class="mb-3 mt-3" />
                </mdb-col>
                <mdb-col xl="10" md="11" size="10">
                  <h5 class="font-weight-bold mb-3">
                    {{ $t('command') }}
                  </h5>
                </mdb-col>
              </mdb-row>
              <mdb-row class="mb-3">
                <mdb-col size="1">
                  <mdb-icon icon="share" size="lg" class="mb-3 mt-3" />
                </mdb-col>
                <mdb-col xl="10" md="11" size="10">
                  <h5 class="font-weight-bold mb-3">
                    {{ $t('local') }}
                  </h5>
                </mdb-col>
              </mdb-row>
              <mdb-row class="mb-3 animated fadeInRight">
                <mdb-col size="1">
                  <mdb-icon icon="share" size="lg" class="mb-3 mt-3" />
                </mdb-col>
                <mdb-col xl="10" md="11" size="10">
                  <h5 class="font-weight-bold mb-3">
                    Node.js skills:
                  </h5>
                </mdb-col>
              </mdb-row>
              <mdb-row class="mb-3">
                <mdb-col size="1">
                  <mdb-icon icon="share" size="lg" class="mb-3 mt-3" />
                </mdb-col>
                <mdb-col xl="10" md="11" size="10">
                  <h5 class="font-weight-bold mb-3">
                    NPM, YARN
                  </h5>
                </mdb-col>
              </mdb-row>
              <mdb-row class="mb-3">
                <mdb-col size="1">
                  <mdb-icon icon="share" size="lg" class="mb-3 mt-3" />
                </mdb-col>
                <mdb-col xl="10" md="11" size="10">
                  <h5 class="font-weight-bold mb-3">
                    Express.js
                  </h5>
                </mdb-col>
              </mdb-row>
              <mdb-row class="mb-3">
                <mdb-col size="1">
                  <mdb-icon icon="share" size="lg" class="mb-3 mt-3" />
                </mdb-col>
                <mdb-col xl="10" md="11" size="10">
                  <h5 class="font-weight-bold mb-3">
                    MySQL, PostgreSQL
                  </h5>
                </mdb-col>
              </mdb-row>
              <mdb-row class="mb-3">
                <mdb-col size="1">
                  <mdb-icon icon="share" size="lg" class="mb-3 mt-3" />
                </mdb-col>
                <mdb-col xl="10" md="11" size="10">
                  <h5 class="font-weight-bold mb-3">
                    Sequelize
                  </h5>
                </mdb-col>
              </mdb-row>
              <mdb-row class="mb-3">
                <mdb-col size="1">
                  <mdb-icon icon="share" size="lg" class="mb-3 mt-3" />
                </mdb-col>
                <mdb-col xl="10" md="11" size="10">
                  <h5 class="font-weight-bold mb-3">
                    REST architecture, GraphQL
                  </h5>
                </mdb-col>
              </mdb-row>
            </mdb-col>
          </mdb-row>
        </section>
      </mdb-container>

      <hr color="white" class="my-5">

      <mdb-container class="max">
        <section class="text-center my-5">
          <mdb-row>
            <mdb-row class="intro">
              <mdb-col md="6" class="md-0 mb-4">
                <mdb-card v-animateOnScroll="{animation: 'bounceInLeft'}" class="card-image-entrepeneur">
                  <a href="/portfolio">
                    <div class="hei text-white rgba-black-strong">
                      <div>
                        <h3 class="py-3 font-weight-bold">
                          <strong class="titleSize">{{ $t('portfolio') }}</strong>
                        </h3>
                      </div>
                    </div>
                  </a>
                </mdb-card>
              </mdb-col>
              <mdb-col md="6" class="md-0 mb-4">
                <mdb-card v-animateOnScroll="{animation: 'bounceInRight'}" class="card-image-individual">
                  <a href="/contacts">
                    <div class="hei text-white rgba-black-strong">
                      <div>
                        <h3 class="py-3 font-weight-bold">
                          <strong class="titleSize">{{ $t('contact') }}</strong>
                        </h3>
                      </div>
                    </div>
                  </a>
                </mdb-card>
              </mdb-col>
            </mdb-row>
          </mdb-row>
        </section>
      </mdb-container>
      <a
        id="back-to-top"
        href="#"
        class="sticky back-to-top textColor"
      >
        <mdb-icon icon="angle-double-up" class="fa-3x" />
      </a>
    </mdb-container>
  </div>
</template>

<script>
import { mapState } from 'vuex'
import { mdbContainer, mdbRow, mdbCol, mdbCard, mdbIcon, animateOnScroll, mdbJumbotron } from 'mdbvue'
export default {
  name: 'AboutPage',
  components: {
    mdbContainer,
    mdbRow,
    mdbCol,
    mdbCard,
    mdbIcon,
    mdbJumbotron
  },
  directives: {
    animateOnScroll
  },
  computed: mapState({
    en: state => state.LangModule.en,
    hu: state => state.LangModule.hu
  }),
  created () {
    if (!this.en) {
      this.$i18n.locale = 'hu'
    } else {
      this.$i18n.locale = 'en'
    }
  },
  head () {
    return {
      title: 'Mark Varga',
      meta: [
        {
          hid: 'home',
          name: 'home',
          content: 'introduction mark varga'
        }
      ]
    }
  }
}
</script>
