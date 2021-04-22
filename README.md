## Screenshoot

<div class="row">
  <div class="column">
    <img src="1.png"  style="width:100%">
  </div>
  <div class="column">
    <img src="2.png"  style="width:100%">
  </div>
  <div class="column">
    <img src="3.png"  style="width:100%">
  </div>
  <div class="column">
    <img src="4.png"  style="width:100%">
  </div>
  <div class="column">
    <img src="5.png"  style="width:100%">
  </div>
</div>
<style>
/* Three image containers (use 25% for four, and 50% for two, etc) */
.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}

/* Clear floats after image containers */
.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>
