<template>
  <v-container>
    <center>
      <div>
        <h1>กิจกรรมแผนกวิชาเทคโนโลยีสารสนเทศ</h1>
        <div class="my-5">
          <nuxt-link to="act1">
            <v-btn color="pink darken-4" dark>
              กิจกรรมหน้าเสาธง
            </v-btn>
          </nuxt-link>

          <nuxt-link to="act2">
            <v-btn color="pink accent-3" dark>
              กิจกรรมโฮมรูม
            </v-btn>
          </nuxt-link>

          <nuxt-link to="act3">
            <v-btn color="red darken-4" dark>
              กิจกรรมชมรม
            </v-btn>
          </nuxt-link>

          <nuxt-link to="act4">
            <v-btn color="deep-purple " dark>
              กิจกรรมพิเศษ
            </v-btn>
          </nuxt-link>

          <nuxt-link to="act5">
            <v-btn color="cyan darken-3" dark>
              กิจกรรมลูกเสือ
            </v-btn>
          </nuxt-link>
        </div>
      </div>
    </center>
  </v-container>
</template>
