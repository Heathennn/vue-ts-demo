<template>
  <div class="about">
    <h1>This is an about page{{msg}}</h1>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';
export default class About extends Vue {
    msg: string = '11'
}
</script>
