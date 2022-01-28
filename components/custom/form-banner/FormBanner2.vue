<template>
  <div>
    <div class="mini-spacer">
      <v-container>
        <!-- -----------------------------------------------
            Start Contact Form
        ----------------------------------------------- -->
        <v-row justify="center">
          <v-col cols="12" sm="10" md="12" lg="8">
            <div>
              <h4 class="font-weight-medium contact-title mt-0">
                Design
              </h4>
              <form>
                <v-row class="mt-15">
                  <v-col cols="12" class="py-0">
                    <v-textarea
                      name="Theme"
                      outlined
                      label="Theme"
                      rows="1"
                    ></v-textarea>
                  </v-col>
                  
                  <v-col cols="12" class="py-0">
                    <v-textarea
                      name="Background Color"
                      outlined
                      label="Background Color"
                      rows="1"
                    ></v-textarea>
                  </v-col>

                  <v-col cols="12" class="py-0">
                    <v-textarea
                      name="Font"
                      outlined
                      label="Font"
                      rows="1"
                    ></v-textarea>
                  </v-col>

                  <v-col cols="12" class="py-0">
                    <v-textarea
                      name="Layout Design"
                      outlined
                      label="Layout Design"
                      rows="1"
                    ></v-textarea>
                  </v-col>
                </v-row>
                <v-btn
                  nuxt
                  to="/landing-page"
                  class="btn-custom-md btn-danger-gradient mt-12"
                  outlined
                  color="white"
                  elevation="0"
                >
                  Back
                </v-btn>

                <v-btn
                  nuxt
                  to="/landing-page2"
                  class="btn-custom-md btn-danger-gradient mt-12"
                  outlined
                  color="white"
                  elevation="0"
                >
                  Next
                </v-btn>
              </form>
            </div>
          </v-col>
        </v-row>
        <!-- -----------------------------------------------
            End Contact Form
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
<script>
export default {
  name: "Contact",
  data() {
    return {
      name: "",
      email: "",
    };
  },
  methods: {},
};
</script>
