<template>
  <div>
    <v-row justify="center" align="center">
      <v-col cols="12" sm="8" md="6">
        <div
          class="pa-7 white rounded-circle d-inline-block margin-top:100px"
        >
          <v-icon color="black" large>
            mdi-cloud-upload
          </v-icon>
        </div>
      </v-col>
    </v-row>
    <h1>HOME ROOM</h1>
    <h3>mobile app</h3>
    <v-form>
      <v-container>
        <v-row>
          <v-col
            cols="12"
            sm="6"
            md="4"
          >
            <v-text-field
              label="Please enter your password"
              placeholder="password"
              filled
              rounded
              dense
            />
            <v-btn
              class="btn1"
            >
              <span class="txt1"> LOGIN </span>
            </v-btn>
            <p>Forgot password?</p>
            <p>New to bang app? Sign up</p>
          </v-col>
        </v-row>
      </v-container>
    </v-form>
  </div>
</template>

<style>
.pa-7{
  margin-top:100px ;
}
h3{
  margin-bottom: 50px;
}
.txt1{
  color: rgb(255, 255, 255);
}
.btn1{
  background: linear-gradient(to bottom,#FFEB3B,#FFC107);
  margin-bottom: 50px;
}
</style>
