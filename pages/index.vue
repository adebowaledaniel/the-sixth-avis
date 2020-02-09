<template>
  <full-page ref="fullpage" :options="options" id="fullpage">
  <v-row class="ma-0 pa-0">
    <!-- 
      TODO: read more on spacing classes https://vuetifyjs.com/en/styles/spacing
     -->
    <v-col cols="12">
      <v-carousel hide-controls vertical-delimiters vertical height="850" continuous>
        <v-carousel-item
          v-for="(slide, index) in mainSlide"
          :key="index"
          :src="slide"
          :class="`red darken-${index} main-slide`"
        >
          <!-- 
            TODO: Design this slide how it is presented on the mockup
           -->
          <v-container fill-height>
            <v-row>
              <v-col cols="12">
                <!-- 
                  TODO: read more on typography https://vuetifyjs.com/en/styles/typography
                 -->
                <h3 class="text-center" >
                  {{ slide.tagline }}
                </h3>
                <span>
                </span>
                <p class="text-center display-4 font-weight-regular">
                  {{ slide.smallTagline }}
                </p>
                <h2 class="top-right display-3 t" >
                  {{ slide.taglinepg }}
                </h2>
              </v-col>
            </v-row>
          </v-container>
        </v-carousel-item>
      </v-carousel>
    </v-col>
  </v-row>
  </full-page>
</template>

<script>
const Slides = [
  {
    tagline: 'WE IMPACT CHANGE',
    smallTagline: 'Tap into the infinite possibilities that come with having the right data.',
    src:
      "https://res.cloudinary.com/the-sixth-avis/image/upload/v1580595470/the-sixth-avis/landing_page1_y11rf0.png"
  },
  // TODO: Write the contents for the main carousel slides here
  // TODO: replace the contents of the slides
  {
    taglinepg: 'Using Data To Predict The Future',
    taglinepg2: 'Who We Are',
    taglinepg2cnt: 'We are a Geospatial and Data Analytics company that works with businesses in identifying patterns, predicting occurrences, and creating sustainable solutions that challenge improvement.',
    taglinepg3: 'Why We Do It',
    taglinepg3cnt: 'To help solve some of Africa’s most difficult problems.',
    src:
      "https://res.cloudinary.com/the-sixth-avis/image/upload/v1580595468/the-sixth-avis/landing_page2_w6wptd.png"
  },
  {
    src:
      "https://res.cloudinary.com/the-sixth-avis/image/upload/v1580595467/the-sixth-avis/landing_page3_ethry3.png"
  },
  {
    src:
      "https://res.cloudinary.com/the-sixth-avis/image/upload/v1580595461/the-sixth-avis/landing_page4_cktpyk.png"
  }

];

export default {
  name: 'home',
  data() {
    return {
      mainSlide: Slides,

      options: {
                  afterLoad: this.afterLoad,
              },
          
      

      methods: {
          afterLoad() {
              console.log("Emitted 'after load' event.");
          }
      },

      
    }
  }
};
</script>

<style>
.main-slide {
  height: '100vh'
}
.top-right{
  position: absolute;
  top: 190px;
  right: 16px;
  
}
</style>