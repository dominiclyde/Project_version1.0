<template>
<div>
  <div class="row">
    <div class="col-md-4">
    <b-card
      title="URGENT NEED FOR DRINKING WATER !!!!!"
      img-src="https://www.clipartkey.com/mpngs/m/294-2947814_clip-art-e-uk-transp-red-emergency-logo.png"
      img-alt="Image"
      img-top
      tag="article"
      style="max-width: 30rem"
      class="mb-2 shadow p-3 mb-5 bg-white rounded "
      border-variant="danger"
    >
      <b-card-text>
        <ul>
          <li>Location: <u>Barangay Poblacion Cebu City</u></li>
          <li>Date: <u>January 5, 2022</u></li>
          <li>Type of Emergency: <u>Loss of Utilities/Services</u></li>
          <li>Name of Contact: <u>Juan dela Cruz</u></li>
          <li>Contact no: <u>091234567890</u></li>
          <li>Type of Contact: <u>Individual</u></li>
          <li>Description:<u> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</u> </li>
        </ul>
      </b-card-text>

      <b-button href="#" variant="primary">Edit</b-button>
      <b-button href="#" variant="danger" class="mx-2">Delete</b-button>
      <b-button href="#" variant="success">Done</b-button> </b-card
    ><br />
    </div>
</div>

</div>
</template>

<script>
export default {
  props: ["Card"],
};
</script>