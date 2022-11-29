<template>
  <div>
    <TheHeader />
    <TheMain 
      v-bind:LeftItems = LeftItems
      v-bind:RightItems = RightItems
    />
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue';
import TheMain from './components/TheMain.vue';
export default {
  name: 'App',

  components: {
    TheHeader,
    TheMain,
  },
  data(){
    return {
      LeftItems:[
        {id: 1, title: "Текущий баланс:", value: "12,00 TJS",option:"+ Пополнить" },
        ],
      RightItems: [
        {id: 2, title: "Ваш тариф:", value: "Биё! Фаъол бош - Сотрудник",option:"Сменить тариф" },
        {id: 3, title: "Остатки минут по РТ:", value: "102 минуты",option:"Подключай минуты +" },
        {id: 4, title: "Остатки интернет трафика:", value: "987 МБ",option:"Подключай мегабайты +" },
        {id: 5, title: "Остатки бонусных баллов:", value: "150",option:"Обменять" },
              ]
            }
        },
}
</script>

<style>
#app{
    margin: 0;
    padding: 0;
    font-family:sans-serif;
    box-sizing: border-box;
}
</style>
