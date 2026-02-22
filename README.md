<h1>Thank You <span class="smile"></span></h1>

<style>
.smile {
  display: inline-block;
  width: 30px;
  height: 30px;
  background: yellow;
  border-radius: 50%;
  position: relative;
  vertical-align: middle;
  margin-left: 10px;
}

.smile::before, .smile::after {
  content: '';
  position: absolute;
  top: 8px;
  width: 5px;
  height: 5px;
  background: black;
  border-radius: 50%;
}

.smile::before { left: 7px; }   /* левый глаз */
.smile::after { right: 7px; }   /* правый глаз */

.smile span {
  position: absolute;
  bottom: 7px;
  left: 50%;
  width: 14px;
  height: 7px;
  border-bottom: 2px solid black;
  border-radius: 0 0 20px 20px;
  transform: translateX(-50%);
}
</style>
