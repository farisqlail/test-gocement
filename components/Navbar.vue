<template>
  <div>
    <b-navbar toggleable="lg" type="light" variant="white">
      <b-navbar-brand to="/"><Logo /></b-navbar-brand>
      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-button class="btn-hub"
          ><i class="bx bxl-whatsapp"></i> Hubungi Kami</b-button
        >
      </b-navbar-nav>
    </b-navbar>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";
export default {
  name: "Navbar",
  components: {
    Logo,
  },
};
</script>

<style>
.btn-hub {
  background: #f67d20;
  border-radius: 4px;
  border: none;
}

.btn-hub:hover {
  background: transparent;
  border-radius: 4px;
  color: #f67d20;
  border: 2px solid #f67d20;
}
</style>