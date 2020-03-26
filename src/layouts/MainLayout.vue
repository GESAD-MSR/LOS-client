<template>
  <q-layout view="lHh Lpr lFf">
    <q-header>
      <q-toolbar class="bg-grey-2">
        <q-toolbar-title class="q-pa-lg text-weight-bold text-uppercase">
          <span class="text-grey-10">Stack</span>
          <span class="text-orange-9 ">Over</span>
          <span class="text-grey-10">Learning</span>
        </q-toolbar-title>

        <q-btn
         flat
         dense
         round
         icon="code"
         color="black"/>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>

export default {
  name: 'MainLayout',

  components: {
  },

  data () {
    return {
    }
  }
}
</script>
