<template>
  <q-page class="bg-white-3 column">
    <Searchbar/>
    <ContentArea/>
    <!-- <DiscussionList/> -->
  </q-page>
</template>

<script>
import Searchbar from '../components/Searchbar'
// import DiscussionList from '../components/DiscussionList'
import ContentArea from '../components/ContentArea'

export default {
  name: 'Home',
  components: {
    Searchbar,
    ContentArea
    // DiscussionList
  }
}
</script>
