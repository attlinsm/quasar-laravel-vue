<template>
  <q-page id="addRoute">
    <q-toolbar class="text-white bg-teal-8">
      <q-toolbar-title>
        Add route
      </q-toolbar-title>
      <q-btn to="/route/saved-routes" flat round dense icon="favorite" color="red" />
    </q-toolbar>

    <q-scroll-area class="form-style q-pa-md">
      <div class="text-h6 q-pb-md">
        Save your favorite route
      </div>

      <span class="text-body1 q-pd-md">
        Pick a name for this route
      </span>

      <q-input outlined stack-label label="Name">
        <template v-slot:append>
          <q-icon name="close"/>
        </template>
      </q-input>

      <div class="text-body1 q-pt-md">
        Save your favorite routes
      </div>

      <q-input outlined stack-label label="From">
        <template v-slot:append>
          <q-icon name="close"/>
        </template>
      </q-input>

      <q-input class="q-pt-md" outlined stack-label label="To">
        <template v-slot:append>
          <q-icon name="close"/>
        </template>
      </q-input>

      <div class="q-pt-md">
        <q-btn size="lg" class="full-width" color="black" label="Save Route"/>
      </div>
    </q-scroll-area>
  </q-page>
</template>

<script>

</script>

<style lang="scss">
#addRoute {
  .form-style {
    margin: 0 auto;
    height: calc(100vh - 180px);
    max-width: 500px;
  }
}
</style>
