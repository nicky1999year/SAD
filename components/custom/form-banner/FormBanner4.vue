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
                E-commerce Features
              </h4>
              <form>
                <v-row class="mt-15">
                  <v-col cols="12" class="py-0">
                    <span style="font-weight:normal; font-size:18px; color:gray;">
                      <input type="checkbox" id="features" value="Social Media" v-model="checkedNames">
                      <label for="Social Media">&nbsp;&nbsp;Social Media buttons</label><br>

                      <input type="checkbox" id="features" value="Online Order" v-model="checkedNames">
                      <label for="Online Order">&nbsp;&nbsp;Online ordering (Pick-up or Delivery service.)</label><br>

                      <input type="checkbox" id="feature" value="payment" v-model="checkedNames">
                      <label for="payment">&nbsp;&nbsp;Payment gateway (for food order or any reservation made)</label><br>

                      <input type="checkbox" id="feature" value="map" v-model="checkedNames">
                      <label for="map">&nbsp;&nbsp;Maps</label><br>

                      <input type="checkbox" id="feature" value="search" v-model="checkedNames">
                      <label for="search">&nbsp;&nbsp;Search box</label><br><br>
                  </span>
                  </v-col>
                </v-row>
                
                <v-btn
                  nuxt
                  to="/landing-page2"
                  class="btn-custom-md btn-danger-gradient mt-12"
                  outlined
                  color="white"
                  elevation="0"
                >
                  Back
                </v-btn>
                
                <v-btn
                  nuxt
                  to="/"
                  class="btn-custom-md btn-danger-gradient mt-12"
                  outlined
                  color="white"
                  elevation="0"
                >
                  Submit
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
