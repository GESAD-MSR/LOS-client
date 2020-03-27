<template>
  <div class="column">
    <div class="row">
      <div class="col-3">
        <TopicsStats/>
      </div>

      <div class="col-9">
        <DiscussionList/>
      </div>
    </div>
  </div>
</template>

<script>

import DiscussionList from '../components/DiscussionList'
import TopicsStats from '../components/TopicsStats'

export default {
  components: {
    DiscussionList,
    TopicsStats
  }
}
</script>
