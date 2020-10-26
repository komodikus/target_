<template>
  <v-app>

  <Header />

    <v-main>
      <MainPage/>
    </v-main>

    <Footer />
  </v-app>
</template>

<script>
import MainPage from "@/components/MainPage";
import Header from "@/components/Header";
import Footer from "@/components/Footer";

export default {
  name: 'App',

  components: {
    Footer,
    Header,
    MainPage,
  },

  data: () => ({
    //
  }),
};
</script>
