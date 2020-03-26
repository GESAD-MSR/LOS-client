<template>
  <q-page class="bg-grey-3 column">
    <Searchbar/>
  </q-page>
</template>

<script>
import Searchbar from '../components/Searchbar'

export default {
  name: 'Home',
  components: {
    Searchbar
  }
}
</script>
