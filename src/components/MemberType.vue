<script type="module">
import { createApp } from 'vue'

defineProps({
  title: {
    type: String,
    required: true
  },
  cost: {
    type: String,
    required: true
  },
  description: {
    type: String,
    required: true
  }
})

createApp({}).mount('#app')
</script>

<template>
  <div class="member-type">
    <h2>{{ title }}</h2>
    <h1>{{ cost }}</h1>
    <div class="description">{{ description }}</div>
    <div class="requirements">Requirements</div>
    <div class="requirement requirement-legal-name">Legal Name</div>
    <div class="requirement requirement-mailing-address">Mailing Address</div>
    <div class="requirement requirement-valid-email-address">Valid Email Address</div>
    <div class="requirement requirement-ssn-itin">SSN/ITIN</div>
    <div class="requirement requirement-age-requirement">Must be 18 or older to apply online*</div>
  </div>
</template>
