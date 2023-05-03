<script type="module">
import { createApp } from 'vue'
import MemberType from './components/MemberType.vue'

export default {}

createApp({}).mount('#app')
</script>

<template>
  <div class="signup">
    <MemberType
      title="Writer & Publisher"
      cost="Free"
      description="ASCAP royalties are split evenly between writers and publishers. Join as both to ensure you get paid everything you deserve."
    />
    <MemberType
      title="Writer"
      cost="Free"
      description="Writers create musical compositions: the melody, harmony, lyrics, beats, arrangements, etc."
    />
    <MemberType
      title="Sign Up"
      cost="$0"
      description="Publishers handle the business side of musical compositions, like licensing and copyright administration."
    />
  </div>
</template>
