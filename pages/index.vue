<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-flex
      xs12
      sm8
      md6
    >
      <v-container>
      <v-parallax
        dark
        src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"
        width=100%
      >
        <v-row
          align="center"
          justify="center"
        >
          <h1 class="display-2 font-weight-thin mb-4">Welcome to udoooom's site.</h1>
        </v-row>
      </v-parallax>
      </v-container>



      <section class="top--wrapper">
        <v-container>
      <v-card
        class="card"
      >
        <h2>About</h2>

        <v-card-text>

          <v-layout justify-center>
          <table>
            <tr>
              <th class="content--tag">Name:</th>
              <th>Daichi Horita(堀田 大地)</th>
            </tr>
            <tr>
              <th class="content--tag">Univ:</th>
              <th>電気通信大学 柳井研究室 B4</th>
            </tr>
            <tr>
              <th class="content--tag">GitHub:</th>
              <th><a href="https://github.com/UdonDa" target="_blank" rel="noopener noreferrer">UdonDa</a></th>
            </tr>
            <tr>
              <th class="content--tag">Twitter:</th>
              <th><a href="https://twitter.com/udoooom" target="_blank" rel="noopener noreferrer">@udoooom</a></th>
            </tr>
            <tr>
              <th class="content--tag">Blog:</th>
              <th><a href="http://udoooom.hatenablog.com/" target="_blank" rel="noopener noreferrer">udoooom's diary</a></th>
            </tr>
            <tr>
              <th class="content--tag">Email:</th>
              <th>udooom0727[at]gmail.com</th>
            </tr>
          </table>
          <!-- <hr class="my-3"> -->
          </v-layout>
        </v-card-text>
      </v-card>
      </v-container>
      </section>

      <section class="top--wrapper">
        <v-container>

        <v-card
          class="card">
          <h2>Publications</h2>
        </v-card>

        <v-layout justify-center class="content--publications">

          <v-layout>
          <v-card
            class="content--work"
          >
            <v-card-title class="content--work--title">DeepTaste: Augmented Reality Gustatory Manipulation with GAN-based Real-time Food-to-food Translation</v-card-title>
            <v-card-text>
              <p>Kizashi Nakano*, <u><b>Daichi Horita*</b></u>, Nobuchika Sakata, Kiyoshi Kiyokawa, Keiji Yanai, and Takuji Narumi (*) equally contributed</p>
              <p>Proc. IEEE International Symposium on Mixed and Augmented Reality (ISMAR) Beijing, China, Oct. 2019(Oral), acceptance rate x%.</p>
            </v-card-text>
          </v-card>
          </v-layout>

          <br>
          <v-card
            class="content--work"
          >
            <v-card-title class="content--work--title">DeepTaste: Augmented Reality Gustatory Manipulation with GAN-based Real-time Food-to-food Translation</v-card-title>
            <v-card-text>
              <p>Kizashi Nakano*, <u><b>Daichi Horita*</b></u>, Nobuchika Sakata, Kiyoshi Kiyokawa, Keiji Yanai, and Takuji Narumi (*) equally contributed</p>
              <p>Proc. IEEE International Symposium on Mixed and Augmented Reality (ISMAR) Beijing, China, Oct. 2019(Oral), acceptance rate x%.</p>
            </v-card-text>
          </v-card>

        </v-layout>
        </v-container>
      </section>

  </v-flex>

  </v-layout>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>

<style scoped>
.top--wrapper{
  margin:0;
}
.card{
  /* width: 100%; */
  padding:30px 90px;
  text-align: center;
}

.content--tag{
  padding-right:20px;
  font-weight:400;
}

.content--publications{
  /* background-color: */
}

.content--work{
  padding:20px 20px;
  margin: 0 0 20px;
  width: 100%;
  box-shadow: 0 0 10px 0 rgba(255,255,255,.2);
}

.content--work--title{
  font-size: 80%;
}
</style>
