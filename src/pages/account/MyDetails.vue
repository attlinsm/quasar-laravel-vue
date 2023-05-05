<template>
  <q-page id="myDetails">
    <q-toolbar class="text-white bg-teal-8">
      <q-toolbar-title>
        My Details
      </q-toolbar-title>
    </q-toolbar>

    <div class="form-style">

      <div class="q-pa-md q-gutter-md">
        <div class="text-h6">
          Update your details
        </div>
        <q-input outlined stack-label label="First Name">
          <template v-slot:append>
            <q-icon name="close"/>
          </template>
        </q-input>

        <q-input outlined stack-label label="Last Name">
          <template v-slot:append>
            <q-icon name="close"/>
          </template>
        </q-input>

        <div class="text-yellow-10 text-bold q-mt-md">
          NOTE: This email is readonly
        </div>

        <q-input outlined stack-label readonly label="Email"/>

        <div>
          <q-btn label="Update Details" color="black" size="lg" class="full-width"/>
        </div>

      </div>
    </div>
  </q-page>
</template>

<script>

</script>

<style lang="scss">
#myDetails {
  .form-style {
    margin: 0 auto;
    height: calc(100vh - 180px);
    max-width: 500px;
  }
  .no-account {
    font-size: 17px;
  }
}
</style>
