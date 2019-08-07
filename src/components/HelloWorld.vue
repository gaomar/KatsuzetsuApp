<template>
  <v-container>
    <v-layout
      text-center
      wrap
    >
      <v-flex mb-4>
        <h1 class="display-2 font-weight-bold mb-10">
          滑舌チェックしよう！
        </h1>
        <v-btn large color="success" @click="start">スタート</v-btn>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  methods: {
    start () {
      interactiveCanvas.sendTextQuery('スタート');
    }
  }
}
</script>