<template>
    <div class="row q-pa-sm justify-center content-center">
      <div class="q-pl-lg q-pr-lg col-8">
        <q-input
          v-model="text"
          label="Topic"
          dense>

          <template v-slot:append>
            <q-icon v-if="text !== ''" name="close" @click="text = ''" class="cursor-pointer" />
            <q-icon name="search" />
          </template>
        </q-input>
      </div>
    </div>
</template>

<script>
export default {
}
</script>
