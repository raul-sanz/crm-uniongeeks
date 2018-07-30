<template>
  <v-app>
    <app-toolbar/>
    <v-content>
      <router-view/>
    </v-content>
    <app-footer/>
  </v-app>
</template>

<script>
import AppFooter from '@/components/Footer'
import AppToolbar from '@/components/Toolbar'
export default {
  name: 'App',
  components:{ AppToolbar , AppFooter },
  data () {
    return {
      
    }
  }
}
</script>
