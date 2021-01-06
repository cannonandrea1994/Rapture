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
      </div>
      <div class="row">
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12">
          <TeamMember />
        </div>
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12">
          <TeamMember />
        </div>
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12">
          <TeamMember />
        </div>
      </div>
    </section>
    <section class="section">
      <div class="row align-items-center">
        <div class="col-md-4">
          <div class="heading"> 
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
      <div class="col-md-4">
        <Service /></div>
      <div class="col-md-4">
        <Service /></div>
      <div class="col-md-4">
        <Service /></div>
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
    <section>
      <div class="section2">
          <div class="row">
            <div class="website"><Website /></div>
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
.headsection {
  background-image: url("/Background.png");
  display: block;
  height: 100%;
  width: 100%;
  max-width: 1600px;
  max-height: 900px;
}
.section {
  padding: 90px 0; 
}
img {
  max-width: 100%;
}
.col-md-9 {
  width: 100%;
  max-width: 767px;
}
</style>
