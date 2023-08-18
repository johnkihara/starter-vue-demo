<template>
   <div class="container">
    <div class="row">
        <div class="col-md-4">
            <div class="card m">
                <img src="../assets/images/logo.png" alt="">
                <h4>{{ data }}</h4>
            </div>
        </div>
    </div>
   </div>
</template>

<script>
export default {
  name: 'CardView',
  props: {
    data: String
  }
}
</script>

<style scoped>
    .card {
        background-color: #0c9b9b;
        width: 300px;
        height: 300px;
        border-radius: 4px;
        padding: 20px;
        text-align: center;
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
    }
    .card img {
        width: 200px;
        height: 200px;
        margin: 15px auto;
    }
    .card h4 {
        margin: 0;
        color: #333;
        font-size: 20px;
        font-weight: 600;
    }

</style>
