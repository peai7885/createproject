<template>
  <div>
    <md-tabs md-sync-route class="md-accent" >
      <md-tab id="tab-home" md-label="Home" to="/components/tabs" exact></md-tab>
      <md-tab id="tab-posts" md-label="Profile" to="/components/tabs/posts"></md-tab>
      <md-tab id="tab-favorites" md-label="Adress" to="/components/tabs/favorites"></md-tab>
    </md-tabs>
  </div>
</template>

<script>
export default {
  name: 'TemPlat'
}
</script>
<style>
  .md-tabs {
    top: 25px;
  }
</style>
