<template>
  <div class="home">
    <div class="photo">
    <img src="@/assets/fooldalkep.jpg" alt="">
        </div>
     <div class="welcomeText">  Welcome to Feminine to Thrive - a safe and nurturing space that's here to support, inspire and empower women through their big life changes - through the journey of conception, pregnancy and labour, through early motherhood, through that transitional time when a woman has to take on multiple roles and also through menopause.

Your wellbeing is a priority - when You feel good, everyone else around you will feel better too. So allow yourself to be held during these significant moments, immerse yourself in that attitude that self-care, community and observing these special times will not only lift you up, but hold you, heal you, nourish you.
Your life is special, You are special, let's stand up for this experience and make it magical.
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
  }
}
</script>

<style scoped>


  img {
   width: 100%;
    height:500px;
}

.welcomeText {

  font-size: 150%;
  text-align: justify;

  padding-block: 20px;
  padding-left: 20px;
  padding-right: 20px;
}
</style>
