<template>
  <footer class="footer">
    <b-row>
      <b-col class="p-4 active"><formatPaint-icon fillColor="#6592A7" /></b-col>
      <b-col class="p-4"><cloudUpload-icon fillColor="#6592A7" /></b-col>
      <b-col class="p-4"><image-icon fillColor="#6592A7" /></b-col>
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
     padding: 20px 17px;
}
.p-4 {
  padding: 2rem !important;
}
.footer .row .col.active span {
  border-radius: 50%;
  background-color: #6592A7;
}
.footer .row .col.active span svg {
  fill: #edebe8 !important;
}
.footer {
  background-color: #515966;
  /* colors */
  /* 
  424249
  e0dad5
  edebe8
  ff5e2c
   */
}

</style>
