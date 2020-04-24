<template>
  <v-container fluid>
    <v-layout column align-center>
      <img src="@/assets/logo.png" alt="Vuetify.js" class="mb-5">
      <HelloWorld quote="Welcome to Your ASP.NET Core + Vue.js + TypeScript App" author="brought to you by GAB2020" />
    </v-layout>
    <v-slide-y-transition mode="out-in">
      <v-row>        
        <v-col>
          <h1 class="headline">Hello, world!</h1>
          <p>Welcome to your new single-page application, built with: </p>
          <ul>
            <li>
              <a href="https://get.asp.net" target="_blank"> ASP.NET Core</a> and
              <a href="https://msdn.microsoft.com/en-us/library/67ef8sbd.aspx" target="_blank">C#</a> for cross-platform server-side API code</li>
            <li>
              <a href="https://vuejs.org" target="_blank"> Vue.js</a> for client-side code</li>
            <li>
              <a href="https://cli.vuejs.org" target="_blank"> Vue CLI</a> for building, bundling and adding or removing vue plugins</li>
            <li>
              <a href="https://webpack.js.org" target="_blank">Webpack</a> internally used by Vue CLI</li>
            <li>
              <a href="https://vuetifyjs.com" target="_blank">Vuetify</a> for layout and styling</li>
          </ul>

          <h3 class="headline mt-5">Thanks to the sponsors of the Global Azure Bootcamp</h3>
          <ul>
            <li>
              <strong>Microsoft</strong></li>
            <li>ACP</li>
            <li>cubido</li>
            <li>European Cloud Conference</li>
            <li>Fronius</li>
            <li>Guid.New</li>
            <li>HATAHET</li>
            <li>SpectoLogic</li>
            <li>Stroyblok</li>
            <li>Programmierfabrik Hagenberg</li>
            <li>Office 365 Blog</li>
            <li>time cockpit</li>
            <li>Coding Club Linz</li>
          </ul>
        </v-col>
      </v-row>
    </v-slide-y-transition>
  </v-container>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

@Component({
  components: {
    HelloWorld,
  },
})
export default class Home extends Vue {}
</script>
