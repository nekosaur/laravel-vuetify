<template>
  <v-app>
    <v-content>
      <v-container>
        <v-row>
          <v-col class="d-flex justify-center">
            <h1>Laravel + Vuetify</h1>
          </v-col>
        </v-row>
        <v-row>
          <v-col>
            <v-card>
              <v-card-text>
                <v-text-field label="Foo"></v-text-field>
                <v-btn>Bar</v-btn>
              </v-card-text>
            </v-card>
            <div class="sass">
                styled from sfc style block with SASS
            </div>
            <div class="scss">
                styled from sfc style block with SCSS
            </div>
          </v-col>
        </v-row>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
export default {

}
</script>

<style lang="sass">
.sass
  background: map-get($material-light, 'cards')
</style>

<style lang="scss">
.scss {
  background: map-get($material-light, 'cards')
}
</style>
