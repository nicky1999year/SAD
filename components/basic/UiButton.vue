<template>
  <div>
    <div class="mini-spacer">
      <v-container>
        <!-- -----------------------------------------------
            Start Ui Buttons
        ----------------------------------------------- -->
        <v-row justify="center">
          <v-col cols="12" sm="10" md="9" lg="7">
            <div class="text-center">
              <h2 class="ui-title font-weight-bold">Vision</h2>
              <p>
                fdhjsklaksjhdfjkdlsakjshdf
              </p>
            </div>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Ui Buttons
        ----------------------------------------------- -->
      </v-container>
    </div>
    <div>
      <v-container>
        <div class="text-center">
          <div class="btn-groups">
            <v-btn depressed> Normal </v-btn>
            <v-btn depressed color="primary"> Primary </v-btn>
            <v-btn depressed color="accent"> Accent </v-btn>
            <v-btn depressed color="error"> Error </v-btn>
            <v-btn depressed color="warning"> Warning </v-btn>
            <v-btn depressed color="success"> Success </v-btn>
          </div>
        </div>
        <div class="text-center mt-12">
          <div class="btn-groups">
            <v-btn outlined> Normal </v-btn>
            <v-btn outlined color="primary"> Primary </v-btn>
            <v-btn outlined color="accent"> Accent </v-btn>
            <v-btn outlined color="error"> Error </v-btn>
            <v-btn outlined color="warning"> Warning </v-btn>
            <v-btn outlined color="success"> Success </v-btn>
          </div>
        </div>
      </v-container>
    </div>
  </div>
</template>
<script>
export default {
  name: "UiButton",
  data() {
    return {};
  },
  methods: {},
};
</script>
