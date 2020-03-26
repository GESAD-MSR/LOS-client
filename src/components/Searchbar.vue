<template>
    <div class="q-pa-sm bg-white">
    <q-input
      bottom-slots
      v-model="text"
      placeholder="Topic"
      :dense="dense">

        <template v-slot:append>
          <q-icon v-if="text !== ''" name="close" @click="text = ''" class="cursor-pointer" />
          <q-icon name="search" />
        </template>

        <template v-slot:hint>
          Field hint
        </template>
      </q-input>
    </div>
</template>

<script>
export default {
}
</script>
