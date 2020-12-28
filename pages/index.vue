<template>
  <div class="container">
    <div class="row">
        <div class="col-md-9">
          <Header />
          </div>
          <div class="col-md-3"> 
            <Header />
          </div>
    </div>
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
    <section>
      <div class="container">
        <div class="section3">
          <div class="row">
            <div class="col-md-4"><Footer />
            </div>
            <div class="col-md-2"><Footer />
            </div>
            <div class="col-md-2"><Footer />
            </div>
            <div class="col-md-2"><Footer />
            </div>
          </div>
        </div>
      </div>    
    </section>
    <section>
      <div class="container">
        <div class="section4">
          <div class="row">
          </div>
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
import Footer from '@/components/Footer.vue'
import Header from '@/components/Header.vue'
export default {
  components: {
    TeamMember,
    PricingTable,
    Service,
    ServiceBordered,
    Typeography,
    Button,
    Website,
    Footer,
    Header,
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
.col-md-9 {
  width: 100%;
  max-width: 767px;
}
</style>
