<template>
  <div id="fullpage-wrapper" ref="fullpage-wrapper">
    <div class="section has-bg" :style="image1">
      <v-row align="center" justify="center" style="height: 100%">
        <v-col cols="12">
          <v-container>
            <v-row no-gutters justify="center">
              <h6
                class="text-center overline font-weight-medium we-impact-change-title pb-5 mb-10"
              >
                We Impact Change
              </h6>
              <h1
                class="text-left display-3 font-weight-light right-data-caption px-10"
              >
                Tap into the infinite possibilities that come with having the
                right data
              </h1>
            </v-row>
          </v-container>
        </v-col>
      </v-row>
    </div>

    <div class="section has-bg">
      <v-row style="height: 100%">
        <v-col
          cols="12"
          md="6"
          :style="{ height: $vuetify.breakpoint.smAndUp ? '100%' : 'auto' }"
        >
          <v-row align="center" style="height: 100%">
            <v-col cols="12" class="pa-12">
              <h3
                class="text-left display-2 font-weight-light who-we-are  pb-5 mb-7"
              >
                Who We Are
              </h3>
              <p class="text-left subtitle2 font-weight-thin ma-0">
                We are a Geospatial and Data Analytics company that works with
                businesses in identifying patterns, predicting occurrences, and
                creating sustainable solutions that challenge improvement.
              </p>
            </v-col>
          </v-row>
        </v-col>
        <v-col
          cols="12"
          md="6"
          :style="{ height: $vuetify.breakpoint.smAndUp ? '100%' : 'auto' }"
        >
          <v-row class="flex-column" style="height: 100%">
            <v-col>
              <v-row align="center" style="height: 100%">
                <v-col cols="12">
                  <span class="text-left display-1 px-5"
                    >Using Data To Predict the Future</span
                  >
                </v-col>
              </v-row>
            </v-col>
            <v-col>
              <h3 class="display-1 font-weight-light who-we-are pb-5 mt-7">
                Why We Do It
              </h3>
              <p class="text-left subtitle2 font-weight-thin mt-5">
                To help solve some of Africa’s most difficult problems
              </p>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </div>

    <div class="section has-bg" :style="image3">
      <v-row>
        <v-col cols="12">
          <h3
            class="text-center display-1 font-weight-light what-we-do-title pb-5 mt-7"
          >
            What We Do
          </h3>
        </v-col>
        <v-col cols="12">
          <v-container>
            <v-row>
              <v-col cols="6" md="3">
                <v-row class="pa-3">
                  <v-card width="100%" class="about-us-card pa-3">
                    <v-row>
                      <v-col cols="12">
                        <v-row justify="center">
                          <v-icon size="40px" color="black" class="mt-3"
                            >mdi-map-marker</v-icon
                          >
                        </v-row>
                      </v-col>
                      <v-col cols="12">
                        <h5 class="subtitle1 px-3 text-center">
                          Smart Agricultural Intervention
                        </h5>
                      </v-col>
                      <v-col cols="12">
                        <p class="caption text-center px-2 font-weight-thin">
                          We monitor, analyze and create implementable farming
                          models that yield more effective and cost-reducing
                          results.
                        </p>
                      </v-col>
                    </v-row>
                  </v-card>
                </v-row>
              </v-col>
              <v-col cols="6" md="3">
                <v-row class="pa-3">
                  <v-card width="100%" class="about-us-card pa-3">
                    <v-row>
                      <v-col cols="12">
                        <v-row justify="center">
                          <v-icon size="40px" color="black" class="mt-3"
                            >mdi-quadcopter</v-icon
                          >
                        </v-row>
                      </v-col>
                      <v-col cols="12">
                        <h5 class="subtitle1 px-3 text-center">
                          UAV- Drone /Aerial Mapping
                        </h5>
                      </v-col>
                      <v-col cols="12">
                        <p class="caption text-center px-2 font-weight-thin">
                          We provide fast and effective UAV solutions for Aerial
                          surveying and mapping across several industries to
                          support intelligent decision making.
                        </p>
                      </v-col>
                    </v-row>
                  </v-card>
                </v-row>
              </v-col>
              <v-col cols="6" md="3">
                <v-row class="pa-3">
                  <v-card width="100%" class="about-us-card pa-3">
                    <v-row>
                      <v-col cols="12">
                        <v-row justify="center">
                          <v-icon size="40px" color="black" class="mt-3"
                            >mdi-elevation-decline</v-icon
                          >
                        </v-row>
                      </v-col>
                      <v-col cols="12">
                        <h5 class="subtitle1 px-3 text-center">
                          Remote Sensing and Environmental Management
                        </h5>
                      </v-col>
                      <v-col cols="12">
                        <p class="caption text-center px-2 font-weight-thin">
                          We use technologically advanced earth observation data
                          to obtain information that aid environmental planning
                          and management.
                        </p>
                      </v-col>
                    </v-row>
                  </v-card>
                </v-row>
              </v-col>
              <v-col cols="6" md="3">
                <v-row class="pa-3">
                  <v-card width="100%" class="about-us-card pa-3">
                    <v-row>
                      <v-col cols="12">
                        <v-row justify="center">
                          <v-icon size="40px" color="black" class="mt-3"
                            >mdi-desktop-tower</v-icon
                          >
                        </v-row>
                      </v-col>
                      <v-col cols="12">
                        <h5 class="subtitle1 px-3 text-center">
                          Database Development and Management
                        </h5>
                      </v-col>
                      <v-col cols="12">
                        <p class="caption text-center px-2 font-weight-thin">
                          We design simplified database structures that satisfy
                          your operational need
                        </p>
                      </v-col>
                    </v-row>
                  </v-card>
                </v-row>
              </v-col>
            </v-row>
          </v-container>
        </v-col>
      </v-row>
    </div>

    <div class="section has-bg" :style="image4">
      <v-row style="height: 100%">
        <v-col cols="12"
          md="6"
          :style="{ height: $vuetify.breakpoint.smAndUp ? '100%' : 'auto'}">
            <v-row align="center" class="flex-column" justify="center">
              <v-col cols="12">
                <h1 class="text-center display-1">Get In Touch With Us</h1>
              </v-col>
            <v-col cols="12">
              <v-icon size="18px" color="white" class="mt-3">mdi-phone</v-icon>
              <p class="caption px-2 font-weight-thin">
                +234 813 643 8158, +234 706 311 2831
              </p>
            </v-col>
            <v-col cols="12">
              <v-icon size="18px" color="white" class="mt-3">mdi-email</v-icon>
              <p class="caption px-2 font-weight-thin">
                thesixthavis@gmail.com
              </p>
            </v-col>
            </v-row>
        </v-col>
        <v-col cols="12"
          md="6"
          :style="{ height: $vuetify.breakpoint.smAndUp ? '100%' : 'auto'}">
          <v-container>
            <v-row>
              <h2 class="tex-right display-1">The Sixth Avis</h2>
            </v-row>
            <v-row align="center">
              <v-form>
                <v-text-field
                  v-model="name"
                  :counter="50"
                  :rules="nameRules"
                  label="Name"
                  required
                ></v-text-field>
                <v-text-field
                  v-model="email"
                  :rules="emailRules"
                  label="E-mail"
                  required
                ></v-text-field>
                <v-text-field
                  label="Message"
                  :rules="rules"
                  hide-details="auto"
                ></v-text-field>
              </v-form>
            </v-row>

            <v-btn large rounded right>Submit</v-btn>
          </v-container>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
import fullpage from "fullpage.js";

export default {
  name: "home",
  data() {
    return {
      fullpageInstance: {},
      image1: {
        backgroundImage:
          "url(https://res.cloudinary.com/the-sixth-avis/image/upload/v1580595470/the-sixth-avis/landing_page1_y11rf0.png)"
      },
      image2: {
        backgroundImage:
          "url(https://res.cloudinary.com/the-sixth-avis/image/upload/v1580595468/the-sixth-avis/landing_page2_w6wptd.png)"
      },
      image3: {
        backgroundImage:
          "url(https://res.cloudinary.com/the-sixth-avis/image/upload/v1580595467/the-sixth-avis/landing_page3_ethry3.png)"
      },
      image4: {
        backgroundImage:
          "url(https://res.cloudinary.com/the-sixth-avis/image/upload/v1580595461/the-sixth-avis/landing_page4_cktpyk.png)"
      }
    };
  },
  methods: {
    onLeave(origin, destination, direction) {},
    afterLoad: function(origin, destination, direction) {},
    afterRender: function() {},
    afterResize: function(width, height) {},
    afterReBuild: function() {},
    afterResponsive: function(isResponsive) {},
    afterSlideLoad: function(section, origin, destination, direction) {},
    onSlideLeave: function(section, origin, destination, direction) {}
  },

  mounted() {
    this.fullpageInstance = new fullpage("#fullpage-wrapper", {
      //options here
      autoScrolling: true
    });
  }
};
</script>

<style>
.fp-tableCell {
  width: 100%;
}
.about-us-card {
  min-height: 300px;
  background-color: rgba(255, 255, 255, 0.7) !important;
}
.what-we-do-title {
  position: relative;
  display: block;
}
.what-we-do-title:after {
  content: " ";
  position: absolute;
  width: 100px;
  background: #fff;
  height: 5px;
  left: calc(50% - 50px);
  bottom: 0;
}
.who-we-are {
  position: relative;
  display: block;
}
.who-we-are:after {
  content: " ";
  position: absolute;
  width: 100px;
  background: #fff;
  height: 5px;
  left: 10px;
  bottom: 0;
}
.section.has-bg {
  background-position: center center;
  background-size: cover;
}
#div-two {
  float: left;
  width: 50%;
}
</style>
