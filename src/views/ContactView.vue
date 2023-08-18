<template>
    <div class="contact">
        <h1>This is the contact page</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci, expedita?</p>
    </div>
    <div class="cardcontents">
        <CardView col-md-4 data="Start Skateboarding with Kiara"/>
    </div>
</template>

<script>
import CardView from '@/components/CardView.vue'
export default {
  name: 'ContactView',
  components: {
    CardView
  }

}
</script>
