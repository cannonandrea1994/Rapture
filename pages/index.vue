<template>
  <div class="container" style="margin: 0px; padding: 0px">
      <section class="section">
        <Button />
      </section>
      <section class="section">
    </section>
  </div>
</template>

<script>
import TeamMember from '@/components/TeamMember.vue'
import PricingTable from '@/components/PricingTable.vue'
import Service from '@/components/Service.vue'
import ServiceBordered from '@/components/ServiceBordered.vue'
import Typeography from '@/components/Typeography.vue'
import Button from '@/components/Button.vue'
import Website from '@/components/Website.vue'
export default {
  components: {
    TeamMember,
    PricingTable,
    Service,
    ServiceBordered,
    Typeography,
    Button,
    Website
  },
}
</script>

<style> 
</style>
