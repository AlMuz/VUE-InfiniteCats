<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="dark" fixed class="mb-5">
      <router-link to="/" class="navbar-brand">Vue Cats</router-link>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <router-link to="/search" activeClass="active" tag="b-nav-item">Search</router-link>
          <router-link to="/about" activeClass="active" tag="b-nav-item">About</router-link>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <!-- <b-navbar-nav class="ml-auto">
          <b-nav-form>
            <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
            <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
          </b-nav-form>
        </b-navbar-nav> -->
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
</style>
