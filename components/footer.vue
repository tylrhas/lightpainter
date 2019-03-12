<template>
  <footer class="footer">
    <b-row>
      <b-col class="p-4 pb-5 active"><formatPaint-icon fillColor="#984b43" /></b-col>
      <b-col class="p-4 pb-5"><cloudUpload-icon fillColor="#984b43" /></b-col>
      <b-col class="p-4 pb-5"><image-icon fillColor="#984b43" /></b-col>
    </b-row>
  </footer>
</template>
<style>
.footer {
  position: fixed;
  bottom: 0px;
  width: 100%;
}
.footer .row .col {
  text-align: center;
}
.footer .row .col span {
  padding: 28px;
}
.footer .row .col.active span {
  border-bottom-left-radius: 50%;
  border-bottom-right-radius: 50%;
  background-color: #18121e;
}
.footer {
  background-color: #fefefe;
  /* colors */
  /* 
  18121e
  233237
  984b43
  eac674
   */
}

</style>
