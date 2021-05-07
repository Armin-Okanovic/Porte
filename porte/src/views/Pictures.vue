<template>
 <div class="pictures">
  <h2>
    Her er nogle af mine art og billeder som jeg har fået taget. Elsker at tage billeder af, naturen, street, kulturen, min bil osv..
</h2>  


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
 </div>
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
                    imgName: require("../assets/1.jpg")
                },

                {
                    imgName: require("../assets/2.jpg")
                },
                  
  
                {
                    imgName: require("../assets/3.jpg")
                },
                
                {
                    imgName: require("../assets/4.jpg")
                },

                {
                    imgName: require("../assets/5.jpg")
                },

                {
                    imgName: require("../assets/7.jpg")
                },

                {
                    imgName: require("../assets/8.jpg")
                },

                {
                    imgName: require("../assets/9.jpg")
                },
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

  



