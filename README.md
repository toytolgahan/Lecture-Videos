<style>
.box {
  border: 1px solid black;
  padding: 10px;
  width: 200px;
  height: 100px;
  display: inline-block;
  position: relative;
}

.arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-top: 10px solid transparent;
  border-bottom: 10px solid transparent;
  border-right: 10px solid black;
  top: 50%;
  margin-top: -10px;
}

.arrow.right {
  left: 200px;
}

.arrow.left {
  right: 200px;
}

</style>

<div class="box">
  Box 1
</div>

<div class="arrow right"></div>

<div class="box">
  Box 2
</div>

<div class="arrow left"></div>

<div class="box">
  Box 3
</div>
