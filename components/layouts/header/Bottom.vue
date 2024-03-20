<template>
  <div class="header-bottom">
    <div class="container d-flex justify-between align-center gap-11">
        <div class="d-flex justify-center align-center text-gray font-regular cursor-pointer all-catalog gap-2" v-for="item of list" :key="item.id">
            <img src="@/assets/icons/shenken.svg" alt="">
            <span>{{item.title}}</span>
        </div>
        <div class="d-flex justify-center align-center text-orange font-regular cursor-pointer all-catalog gap-2">
            <span>Ещё</span>
            <img src="@/assets/icons/orange-arrow.svg" alt="">
        </div>
        
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
        list:[
            {
                id: 1,
                title: 'Подарки'
            },
            {
                id: 2,
                title: 'Мебель'
            },
            {
                id: 3,
                title: 'Техника'
            },
            {
                id: 4,
                title: 'Текстиль'
            },
            {
                id: 5,
                title: 'Посуда'
            },
            {
                id: 6,
                title: 'Стройматириалы'
            },
            {
                id: 7,
                title: 'Канцтовары'
            },
            {
                id: 8,
                title: 'Акции'
            },
        ]
    }
  },
}
</script>

<style lang="scss">
    @import '@/styles/layouts/header.scss';
</style>