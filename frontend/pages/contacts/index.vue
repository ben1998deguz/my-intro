<template>
  <div class="">
    <div class="parallaxContact" />
    <mdb-container>
      <section class="my-5">
        <h2 class="h1-responsive font-weight-bold text-center my-5">{{ $t('contact') }}</h2>
        <p class="text-center w-responsive mx-auto pb-5">{{ $t('interest') }}</p>
        <mdb-row>
          <mdb-col lg="12">
            <div id="map-container" class="rounded z-depth-1-half map-container" style="height: 400px">
              <iframe src="https://maps.google.com/maps?width=100%25&amp;height=600&amp;hl=en&amp;q=Budapest+(My%20Business%20Name)&amp;t=&amp;z=9&amp;ie=UTF8&amp;iwloc=B&amp;output=embed" width="100%" height="100%" frameBorder="0" style="border: 0" />
            </div>
            <br/>
            <mdb-row class="text-center">
              <mdb-col md="4">
                <mdb-icon size="2x" class="mb-3" icon="map-marker"/>
                <p>Budapest</p>
              </mdb-col>
              <mdb-col md="4">
                <mdb-icon size="2x" class="mb-3" icon="phone"/>
                <p>+ 36 30 517 54 22</p>
                <p class="mb-md-0">{{ $t('days') }} 8:00-22:00</p>
              </mdb-col>
              <mdb-col md="4">
                <mdb-icon size="2x" class="mb-3" icon="envelope"/>
                <p>markweb.varga@gmail.com</p>
              </mdb-col>
            </mdb-row>
            <mdb-row class="text-center mt-5">
              <mdb-col lg="12" class="m-1">
                <a href="https://www.facebook.com/vargabeni69/">
                  <mdb-icon fab icon="facebook-f" class="fa-3x mr-4 mt-3" />
                </a>
                <a href="https://www.linkedin.com/in/varga-mark-61796a197/">
                  <mdb-icon fab icon="linkedin" class="fa-3x" />
                </a>
              </mdb-col>
            </mdb-row>
          </mdb-col>
        </mdb-row>
      </section>
    </mdb-container>
  </div>
</template>

<script>
import { mapState } from 'vuex'
import { mdbContainer, mdbRow, mdbCol, mdbIcon } from 'mdbvue'

export default {
  components: {
    mdbContainer,
    mdbRow,
    mdbCol,
    mdbIcon
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
