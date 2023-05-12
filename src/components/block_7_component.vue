<template>
  <div class="block_7">
      <div class="background_block">
        <div class="text_block_7">
          <div class="text">
            <p class="prepod">ПРЕПОДАВАТЕЛИ</p>
            <p class="matem">Математика</p>
            <p>Русский язык</p>
            <p>Обществознание </p>
            <p>Информатика</p>
            <p>Экономика</p>
          </div>
        <div class="img_block_7">
          <img src="../img/123213.png" class="photo">
          <p class="maria">МАРИЯ ДОБРЫНИНА</p>
          <div class="text_block_img">
            <p class="p">Образование</p>
            <p class="p">Статистика</p>
            <p class="p">Что то от преподователей</p>
            <p class="p">Текст</p>
            <p class="p">Текст</p>
          </div>
        </div>
        </div>
          <img src="../img/layers-1.png" class="eclipse1">
<!--          <img src="../img/Ellipse2.svg" class="eclipse2">-->
<!--          <img src="../img/Ellipse3.svg" class="eclipse3">-->
<!--          <img src="../img/Ellipse4.svg" class="eclipse4">-->
      </div>
  </div>
</template>

<script>
export default {
  name: "block_7_component"
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&family=Space+Grotesk:wght@300;400;500;600;700&display=swap');
.background_block{
  background: linear-gradient(180deg, #D0A0FF 17.65%, rgba(214, 171, 255, 0.800263) 30.01%, rgba(234, 208, 255, 0.08) 84.74%);
  height: 900px;
}
.prepod{
  font-family: 'Space Grotesk', sans-serif;
  font-size: 36px;
  font-weight: 700;
  color: black;;
}
.p{
  margin: 0;
  text-align: left;
}
.maria{
  font-weight: 800;
  margin: 10px 0 5px;
}
.text{
  font-family: 'Inter', sans-serif;
  font-weight: 500;
  font-size: 22px;
  position: absolute;
  margin: 48px auto 0 auto;
  color: #515151;
  left: 70px;
  text-align: left;
}
.photo{
  width: 200px;
}

.img_block_7{
  position: absolute;
  margin: 95px auto 0 auto;
  color: #515151;
  left: 597px;
  right: 0;
  width: 200px;
}
.matem{
  color: black;
}
.text_block_7{
  display: flex;
  justify-content: center;
}
.eclipse1{
  width: 100%;
  margin: 430px 0 0 0;
}
</style>