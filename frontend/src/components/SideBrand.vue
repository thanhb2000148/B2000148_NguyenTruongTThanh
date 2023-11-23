<template>
   <div class="container">
      <div class="box-container">
         <h3 class="title">Tiêu Chí Bán hàng</h3>
         <p class="intro-text">
            <b>YoTa Food của chúng tôi đảm bảo an toàn vệ sinh thực phẩm và có kiểm định nguồn gốc rõ ràng. Chúng tôi sử dụng công nghệ hiện đại để sản xuất món đồ ăn vặt này và đảm bảo rằng món ăn của chúng tôi luôn đạt chuẩn VSATTP.</b> </p>
      </div>
   </div>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
   setup() {
   },
});
</script>

<style scoped>
.intro-text {
   text-align: center;
   color: #333;
   font-size: 18px;
   margin-top: 20px;
}

.container {
   margin: 0 auto;
}

.box-container {
   height: 150px;
   padding: 0 0;
}

.title {
   text-align: center;
   color: #131212;
   font-size: 26px;
   font-weight: normal;
   border-bottom: 3px solid #e30707;
   margin-bottom: 30px;
   padding: 10px 0;
}
</style>
