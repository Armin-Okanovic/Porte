<template>
  <v-row>
    <v-col
      class="d-flex child-flex"
      cols="6"
      v-for="picture in arrayOfPictures" :key="picture"
    >
      <v-img
        :src="picture.imgName"
        contain
        aspect-ratio="1"
        class="grey lighten-2"
      >
        <template v-slot:placeholder>
          <v-row
            class="fill-height ma-0"
            align="center"
            justify="center"
          >
            <v-progress-circular
              indeterminate
              color="grey lighten-5"
            ></v-progress-circular>
          </v-row>
        </template>
      </v-img>
    </v-col>
        <v-col
      class="d-flex child-flex"
      cols="4"
    >
      
    </v-col>
  </v-row>
</template>

<script>
export default {
    data() {
        return {
            arrayOfPictures : [
                {
                    imgName: require("../assets/poster.png")
                },
                {
                    imgName: require("../assets/armin.png")
                },
                {
                    imgName: require("../assets/ArminAO.png")
                },
                {
                    imgName: require("../assets/hora-kopi.png")
                },
                 {
                    imgName: require("../assets/esbjerg-projekt.png")
                },
                 {
                    imgName: require("../assets/ao-logo.png")
                }
                  
            ]
        }
    },
}
</script>

<style scoped>
    div {
        

        background-color: transparent;
        background-size: auto;
        
        

    }
</style>

  



