<template>
  <div class="block_6">
    <div class="block_6_contnainer">
        <p class="FAQ">FAQ</p>
      <div class="items_block_6">
        <div class="item_block">
          <div class="item">
              <p>Где проходит обучение?</p>
              <p class="plus">+</p>
          </div>
        </div>
        <div class="item_block">
          <div class="item">
            <p>Будут ли записи занятий?</p>
            <p class="plus">+</p>
          </div>
        </div>
        <div class="item_block">
          <div class="item">
            <p>Есть ли личные наставники?</p>
            <p class="plus">+</p>
          </div>
        </div>
        <div class="item_block">
          <div class="item">
            <p>Как проходит контроль успеваемости?</p>
            <p class="plus">+</p>
          </div>
        </div>
        <div class="item_block" id="posl">
          <div class="item">
            <p>Какие есть способы оплаты?</p>
            <p class="plus">+</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "block_6_component"
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&family=Space+Grotesk:wght@300;400;500;600;700&display=swap');

.item{
  display: flex;
  justify-content: space-between;
  padding: 0 30px;
  font-family: 'Space Grotesk', sans-serif;
  font-weight: 700;
  font-size: 25px;
  margin: 5px 0;
}
#posl{
  border-bottom: 2px solid #F1A33F;
}
.plus{
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 45px;
  margin: 5px 0;
}
.FAQ{
  font-family: 'Space Grotesk', sans-serif;
  font-weight: 700;
  font-size: 75px;
  padding: 50px 0 0 0;
  margin: 0 80px 20px;
  text-align: left;
}
.block_6{
  margin: 100px 0 0 0;
}
.items_block_6{
  width: 750px;
  margin: 0 0 0 60px;
}
.item_block{
  border-top: 2px solid #F1A33F;
}
.block_6_contnainer{
  background: #FFE5C4;
  height: 700px;
}
</style>