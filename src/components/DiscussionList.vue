<template>
  <div>
    <div class="q-pa-sm row q-pl-lg justify-left content-center">

      <q-toggle
        class="q-pr-lg"
        color="orange"
        name="filter"
        v-model="hasImage"
        label="Image"
      />

      <q-toggle
        class="q-pr-lg"
        color="orange"
        name="filter"
        v-model="hasCode"
        label="Code"
      />

      <q-toggle
        class="q-pr-lg"
        color="orange"
        name="filter"
        v-model="hasAnswer"
        label="Answered"
      />
    </div>

    <div class="row justify-end">
      <div
        class="col-12"
        v-for="x in 5"
        :key="x">
          <Discussion/>
      </div>
    </div>
  </div>
</template>

<script>

import Discussion from '../components/Discussion'

export default {

  data () {
    return {
      hasImage: true,
      hasCode: true,
      hasAnswer: true
    }
  },

  components: {
    Discussion
  }
}
</script>
