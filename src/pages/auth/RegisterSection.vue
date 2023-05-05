<template>
  <q-page id="registrationPage">
    <q-toolbar class="text-white bg-teal-8">
      <q-toolbar-title>
        Register
      </q-toolbar-title>
    </q-toolbar>

    <div class="form-style">
      <div class="text-h6 text-center q-mt-md">
        <q-img src="favicon.ico" width="60px"/>
        <div>
          Ev Charge Map
        </div>
      </div>

      <div class="q-pa-md q-gutter-md">
        <div class="text-center">
          Register and get extra features
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

        <q-input outlined stack-label label="Email">
          <template v-slot:append>
            <q-icon name="close"/>
          </template>
        </q-input>

        <q-input outlined stack-label label="Password">
          <template v-slot:append>
            <q-icon name="close"/>
          </template>
        </q-input>

        <q-input outlined stack-label label="Confirm password">
          <template v-slot:append>
            <q-icon name="close"/>
          </template>
        </q-input>

        <div>
          <q-btn label="Register" color="black" size="lg" class="full-width"/>
        </div>

      </div>
    </div>

  </q-page>
</template>

<script>

</script>

<style lang="scss">
#registrationPage {
  .form-style {
    margin: 0 auto;
    height: calc(100vh - 180px);
    max-width: 500px;
  }
}
</style>
