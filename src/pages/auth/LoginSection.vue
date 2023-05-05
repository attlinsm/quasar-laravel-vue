<template>
  <q-page id="loginPage">
    <q-toolbar class="text-white bg-teal-8">
      <q-toolbar-title>
        Login
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
          Login before using
        </div>
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

        <div>
          <q-btn label="Sign in" color="black" size="lg" class="full-width"/>
        </div>

        <div class="q-px-md q-mt-xl text-center">
          <div class="q-mb-md no-account">
            Don't have an accout ?
          </div>
          <q-btn color="teal" outline rounded to="/auth/register" size="15px">
            Register Here
          </q-btn>
        </div>

      </div>
    </div>

  </q-page>
</template>

<script>

</script>

<style lang="scss">
#loginPage {
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
