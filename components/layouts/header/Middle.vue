<template>
  <div class="header-middle">
    <div class="container d-flex justify-between align-center">
        <!-- logo -->
        <img src="@/assets/images/logo.svg" alt="logo" class="header-logo">
        <button class="header-catalog d-flex justify-center align-middle">
            <img class="w-4 h-4 mr-3" src="@/assets/icons/frame.svg" alt="">
            <span class="text-orange font-inter">
                Каталог
            </span>
        </button>
        <div class="header-search">
            <input type="text" placeholder="Искать">
            <button class="header-search-btn">
                <img src="@/assets/icons/Search.svg" alt="search" />
            </button>
        </div>
        <div class="header-action d-flex justify-center align-middle gap-2 text-black font-inter cursor-pointer" >
            <img class="w-5 h-5" src="@/assets/icons/Swap.svg" alt="">
            <span>Сравнение</span>
        </div>
        <div class="header-action d-flex justify-center align-middle gap-2 text-black font-inter cursor-pointer" >
            <img class="w-5 h-5" src="@/assets/icons/Heart.svg" alt="">
            <span>Избранное</span>
        </div>
        <div class="header-action d-flex justify-center align-middle gap-2 text-black font-inter cursor-pointer" >
            <img class="w-5 h-5" src="@/assets/icons/Bag.svg" alt="">
            <span>Корзина</span>
        </div>
        <div class="header-action d-flex justify-center align-middle gap-2 text-black font-inter cursor-pointer" >
            <img class="w-5 h-5" src="@/assets/icons/Profile.svg" alt="">
            <span>Войти</span>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    data() {
        return {
            text: ''
        }
    },
}
</script>

<style lang="scss">
    @import '@/styles/layouts/header.scss';
</style>