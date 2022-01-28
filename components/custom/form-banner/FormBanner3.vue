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
                Add Pages.
              </h4>
              <form>
                <v-row class="mt-15">
                  <v-col cols="12" class="py-0">
                      <input type="checkbox" id="page" value="Homepage" v-model="checkedNames">
                      <label for="Homepage">Home Page</label><br>

                      <input type="checkbox" id="page" value="About us" v-model="checkedNames">
                      <label for="About us">About Us</label><br>

                      <input type="checkbox" id="page" value="Contact Us" v-model="checkedNames">
                      <label for="Contact Us">Contact Us</label><br>

                      <input type="checkbox" id="page" value="Register Login" v-model="checkedNames">
                      <label for="Register login">Register / Login Page</label><br>

                      <input type="checkbox" id="page" value="Menu" v-model="checkedNames">
                      <label for="Menu">Menu</label><br>

                      <input type="checkbox" id="page" value="Reservation" v-model="checkedNames">
                      <label for="Reservation">Table Reservation Page</label><br>

                      <input type="checkbox" id="page" value="Blog" v-model="checkedNames">
                      <label for="Blog">Blog Page</label><br>

                      <input type="checkbox" id="page" value="Gallery" v-model="checkedNames">
                      <label for="Gallery">Gallery Page</label><br>

                      <input type="checkbox" id="page" value="Feedback" v-model="checkedNames">
                      <label for="Feedback">Feedback Page</label><br>

                      <input type="checkbox" id="page" value="custom" v-model="checkedNames">
                      <label for="custom">Black Page (You can custom the page yourself.)</label><br>
                    </v-col>
                </v-row>
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
