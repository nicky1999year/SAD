<template>
  <div>
    <div class="feature1-component mini-spacer">
      <v-container>
        <!-- -----------------------------------------------
            Start Feature 1 Text
        ----------------------------------------------- -->
        <v-row justify="center">
          <v-col cols="12" md="10" lg="7">
            <div class="text-center">
              <v-chip small color="error" text-color="white">
                Feature 1
              </v-chip>
              <h2 class="section-title font-weight-medium">
                Launch your entire website RIGHT NOW with ZERO TECH KNOWLEDGE
              </h2>
              <p>
               We create for you the best landing page that conveys an idea to the audience and allows you to collect data about the idea. 
              </p>
            </div>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Feature 1 Text
        ----------------------------------------------- -->
        <!-- -----------------------------------------------
            Start Feature 1
        ----------------------------------------------- -->
        <v-row justify="center" class="mt-13">
          <v-col cols="12" md="6">
            <v-card elevation="0">
              <v-card-text>
                <div class="icon-round bg-light-info">
                  <i class="mdi mdi-star"></i>
                </div>
                <h5 class="font-weight-medium font-18">Fully Guided Website Copywriting</h5>
                <p class="mt-10 mb-8">
                  A copywriter would take approximately 8 hours or more to write a full website copy with adequate planning and multiple rewrites. Avoid the headache by following our guided process and spend the time focusing on your business instead.
                </p>
                <a
                  href="#"
                  class="
                    text-themecolor
                    linking
                    text-decoration-none
                    d-flex
                    align-center
                  "
                >
                  Explore More <i class="mdi mdi-arrow-right"></i>
                </a>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6">
            <v-card elevation="0">
              <v-card-text>
                <div class="icon-round bg-light-info">
                  <i class="mdi mdi-check-circle"></i>
                </div>
                <h5 class="font-weight-medium font-18">Automate Your Website Design</h5>
                <p class="mt-10 mb-8">
                  For start, you could hire a designer and spend hours and money on multiple website variations. Or you could buy a template and spend a monumental effort on editing and fine-tuning. But why do all of that? Sitegen creates beautiful designs for your content at a fraction of the cost and time.
                </p>
                <a
                  href="#"
                  class="
                    text-themecolor
                    linking
                    text-decoration-none
                    d-flex
                    align-center
                  "
                >
                  Explore More <i class="mdi mdi-arrow-right"></i>
                </a>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Feature 1
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
<script>
export default {
  name: "Feature1",
  data() {
    return {};
  },
  methods: {},
};
</script>
