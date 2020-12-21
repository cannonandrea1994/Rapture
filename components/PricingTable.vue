<template>
  <div class="pricing-table">
    <div class="pricing-table__header">
      <span class="pricing-table__package">Standard</span>
      <span class="pricing-table__title"><span>IDR</span> 2500k</span>
      <p class="pricing-table__content">We provide services including domain purchase and hosting.</p>
    </div>
    <div class="pricing-table__body">
      <ul class="pricing-list">
        <li class="pricing-list__item">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <circle opacity="0.1" cx="12" cy="12" r="12" fill="#0CBF9F"/>
            <path d="M17.3334 8L10.0001 15.3333L6.66675 12" stroke="#0CBF9F" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          Full desktop or Browser</li>
        <li class="pricing-list__item">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <circle opacity="0.1" cx="12" cy="12" r="12" fill="#0CBF9F"/>
            <path d="M17.3334 8L10.0001 15.3333L6.66675 12" stroke="#0CBF9F" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          Full desktop or Browser</li>
        <li class="pricing-list__item">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <circle opacity="0.1" cx="12" cy="12" r="12" fill="#0CBF9F"/>
            <path d="M17.3334 8L10.0001 15.3333L6.66675 12" stroke="#0CBF9F" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          Full desktop or Browser</li>
      </ul>
    </div>
    <div class="pricing-table__footer">
      <Button full="true" />
    </div>
  </div>
</template>

<script>
import Button from '@/components/Button.vue'
export default {
  components: {
    Button,
  },
}
</script>

<style lang="scss" scoped>
$accent: #FFA149;
.pricing-table {
  border: 1px solid $accent;
  display: flex;
  flex-direction: column;

  &__header {
    padding: 40px 30px 30px 30px;

    > span {
      display: block;
    }
  }

  &__body {
    padding: 0 30px 30px;
  }

  &__footer {
    width: 100%;
    padding: 30px;
    align-self: center;
    justify-content: flex-end;
    margin-top: auto;
  }

  &__package {
    color: #333333;
    font-family: 'Mulish', sans-serif;
    font-size: 24px;
    line-height: 170%;
    font-weight:  bold;
    margin-bottom: 10px;
  }

  &__title {
    font-weight: 700;
    font-family: 'Mulish', sans-serif;
    font-size: 28px;
    line-height: 170%;
    color: #333333;
    text-transform: uppercase;
    margin-bottom: 10px;
    > span {
      color: #777777;
    }
  }

  &__desc {
    font-weight: 400;
    font-family: 'Mulish', sans-serif;
    font-size: 16px;
    line-height: 170%;
    color: #555555;
    margin-bottom: 0;
  }
}

.pricing-list {
  list-style: none;
  margin: 0;
  padding: 0;
  padding-top: 30px;
  border-top: 1px solid #DDDDDD;

  &__item {
    display: flex;
    align-items: center;
    padding: 10px 0;
    color: #333333;
    font-weight: 700;
    font-size: 16px;
    line-height: 1;
    font-family: 'Mulish', sans-serif;
    svg {
      margin-right: 13px;
    }
  }
}
</style>
