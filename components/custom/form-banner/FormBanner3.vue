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
                Add Pages
              </h4>
              <form>
                <v-row class="mt-15">
                  <v-col cols="12" class="py-0">
                    <span style="font-weight:normal; font-size:18px; color:gray;">
                      <input type="checkbox" id="page" value="Homepage" v-model="checkedNames">
                      <label for="Homepage">&nbsp;&nbsp;Home Page</label><br>

                      <input type="checkbox" id="page" value="About us" v-model="checkedNames">
                      <label for="About us">&nbsp;&nbsp;About Us</label><br>

                      <input type="checkbox" id="page" value="Contact Us" v-model="checkedNames">
                      <label for="Contact Us">&nbsp;&nbsp;Contact Us</label><br>

                      <input type="checkbox" id="page" value="Register Login" v-model="checkedNames">
                      <label for="Register login">&nbsp;&nbsp;Register / Login Page</label><br>

                      <input type="checkbox" id="page" value="Menu" v-model="checkedNames">
                      <label for="Menu">&nbsp;&nbsp;Menu</label><br>

                      <input type="checkbox" id="page" value="Reservation" v-model="checkedNames">
                      <label for="Reservation">&nbsp;&nbsp;Table Reservation Page</label><br>

                      <input type="checkbox" id="page" value="Blog" v-model="checkedNames">
                      <label for="Blog">&nbsp;&nbsp;Blog Page</label><br>

                      <input type="checkbox" id="page" value="Gallery" v-model="checkedNames">
                      <label for="Gallery">&nbsp;&nbsp;Gallery Page</label><br>

                      <input type="checkbox" id="page" value="Feedback" v-model="checkedNames">
                      <label for="Feedback">&nbsp;&nbsp;Feedback Page</label><br>

                      <input type="checkbox" id="page" value="custom" v-model="checkedNames">
                      <label for="custom">&nbsp;&nbsp;Black Page (You can custom the page yourself.)</label><br><br>
                    </span>
                    </v-col>
                </v-row>
                <v-btn
                  nuxt
                  to="/landing-page1"
                  class="btn-custom-md btn-danger-gradient mt-12"
                  outlined
                  color="white"
                  elevation="0"
                >
                  Back
                </v-btn>
                
                <v-btn
                  nuxt
                  to="/landing-page3"
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
