<template>
  <div class="container">
    <div class="row">
      <div class="col-md-12">
        <section class="section">
          <Button />
        </section>
      </div>
    </div>
    <section class="section">
      <div class="heading">
        <h2>Our Team</h2>
      </div>
      <div class="row">
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12">
          <TeamMember img="staff.png" name="Cody Fisher" title="Drug Dealer" />
        </div>
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12">
          <TeamMember img="mid.png" name="Henry Courtney" title="UI/UX Designer" />
        </div>
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12">
          <TeamMember img="title.png" name="Dianne Russel" title="Front End Developer" />
        </div>
      </div>
    </section>
    <section class="section">
      <div class="row align-items-center">
        <div class="col-md-4">
          <div class="heading">
            <h2>Pricing</h2>
            <p> has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, </p>
          </div>
        </div>
        <div class="col-md-4">
          <PricingTable />
        </div>
        <div class="col-md-4">
          <PricingTable />
        </div>
      </div>
    </section>
    <section class="section">
    <div class="row">
      <div class="col-md-4"><Service /></div>
      <div class="col-md-4"><Service /></div>
      <div class="col-md-4"><Service /></div>
    </div>
    <div class="row">
      <div class="col-md-4"><ServiceBordered /></div>
      <div class="col-md-4"><ServiceBordered /></div>
      <div class="col-md-4"><ServiceBordered /></div>
    </div>
    </section>
    <section class="section">
    <div class="row">
      <div class="col-md-12">
        <Typeography />
      </div>
    </div>
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
export default {
  components: {
    TeamMember,
    PricingTable,
    Service,
    ServiceBordered,
    Typeography,
    Button,
  },
}
</script>

<style>
.section {
  padding: 90px 0;
}
img {
  max-width: 100%;
}
</style>
