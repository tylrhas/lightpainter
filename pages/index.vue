<template>
  <div>
    <appHeader/>
    <b-container>
      <b-row>
        <b-col class="p-4">
          <div class="selectedImage mx-auto">
            <b-img v-bind:src="selected" fluid alt="Responsive image"/>
          </div>
        </b-col>
      </b-row>
      <b-row>
        <b-col class="p-3">
        <b-form-select v-model="selected" :options="options"/>
        </b-col>
      </b-row>
      <b-row>
        <b-col class="mx-auto paintButton">
          <b-button variant="outline-primary">Paint</b-button>
        </b-col>
      </b-row>
    </b-container>
    <appFooter/>
  </div>
</template>

<script>
import appHeader from "~/components/header.vue";
import appFooter from "~/components/footer.vue";
export default {
  data() {
    return {
      selected: null,
      options: [
        { value: null, text: "Please select an option" },
        { value: "https://via.placeholder.com/150", text: "Placeholder Image" }
      ]
    };
  },
  components: {
    appHeader,
    appFooter
  }
};
</script>
<style>
.selectedImage {
  text-align: center;
  height: 150px;
}
.paintButton {
  text-align: center;
}
</style>

