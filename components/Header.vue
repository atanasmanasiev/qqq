<template>
<div class="header-container">
  <header class="the-header">
    <!-- <TheSideNavToggle @toggle="$emit('sidenavToggle')" /> -->
    <div class="logo">
      SOURCE TOWN
    </div>
    <div class="spacer"></div>
    <div class="navigation-items">
      <ul class="nav-list">
        <li class="nav-item">Solutions</li>
        <li class="nav-item">Customers</li>
        <li class="nav-item">Support</li>
        <li class="nav-item">Pricing</li>
        <li class="nav-item">Contact</li>
      </ul>
    </div>
  </header>
</div>
</template>

<script>
export default {
  name: "TheHeader",
};
</script>


<style scoped>
.header-container {
  height: 60px;
}

.the-header {
  width: 100%;
  /* position: fixed; */
  height: 60px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: transparent;
  z-index: 100;
  box-sizing: border-box;
  padding: 0 20px;
}


.nav-list {
  list-style: none;
  padding: 0;
  margin: 25px;
  display: flex;
}

.nav-item {
  margin: 0 10px;
    color: #ffffff;

}

.nav-item a {
  text-decoration: none;
  color: #ffffff;
}

.nav-item a:hover,
.nav-item a:active,
.nav-item a.nuxt-link-active {
  color: red;
}
.logo {
  color: #ffffff
}
</style>
