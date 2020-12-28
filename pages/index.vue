<template>
  <div class="container">
    <div class="row">
        <div class="col-md-9">
          <Header />
          <img src="webagency.png" style="max-width: 187px; max-height: 38px;">
          </div>
          <div class="col-md-3"> 
            <Header />
          <b>  About Us     Contact</b> 
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
      <div class="col-md-4">
        <Service img="doctor.png" name="Jerome Bell" /></div>
      <div class="col-md-4">
        <Service img="busdude.png" name="Ronald Richards" /></div>
      <div class="col-md-4">
        <Service img="restlady.png" name="Leslie Knope" /></div>
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
            <img src="webagency.png">
            <br><br>Jalan Gatak, Tamantirto, Kasihan, 
            <br>Bantul, D. I. Yogyakarta 55183
            </div>
            <div class="col-md-2"><Footer />
            <h5>Navigation</h5>
            <br>Portfolio
            <br>Contact
            <br>Feature
            <br>Pricing
            </div>
            <div class="col-md-2"><Footer />
            <h5>About Us</h5>
            <br>FAQ
            <br>Contact
            <br>Feature
            <br>Client
            </div>
            <div class="col-md-2"><Footer />
            <h5>Contact</h5>
            <br>0822 3498 1535
            <br>halo@web.agency
            </div>
          </div>
        </div>
      </div>    
    </section>
    <section>
      <div class="container">
        <div class="section4">
          <div class="row">
            <span class="copyright"><b>© Copyright 2020 web.agency</b></span>
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
.section3 {
  padding-left: 150px;
  padding-bottom: 125px;
}
.section4 {
  padding-top: 125px;
  padding-bottom: 40px;
}
.copyright{
  margin: auto;
}
img {
  max-width: 100%;
}
.col-md-9 {
  width: 100%;
  max-width: 767px;
}
</style>
