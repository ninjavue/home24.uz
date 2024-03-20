<template>
    <div class="header-top bg-gray">
        <div class="container d-flex justify-between">
            <div class="header-location d-flex justify-center align-center font-inter">
                <div class="d-flex justify-end align-bottom mr-2">
                    <img class="w-4 h-4 mr-1" src="@/assets/icons/location.svg" alt="">
                    <span class="text-gray">Город:</span>
                </div>
                <div class="text-black underline cursor-pointer">
                    Ташкент
                </div>
            </div>
            <div class="header-media d-flex justify-center align-center gap-10">
                <a target="_blank" href="https://instagram.com/home24.uz" class="media-insta d-flex justify-center align-center gap-2 font-inter">
                    <img src="@/assets/icons/instagram.svg" alt="i" />
                    <span class="text-gray">home24.uz</span>
                </a> 
                <a target="_blank" href="https://t.me/home24uz" class="media-insta d-flex justify-center align-center gap-2 font-inter">
                    <img src="@/assets/icons/telegram.svg" alt="i" />
                    <span class="text-gray">t.me/home24uz</span>
                </a>
                <a href="tel:9989712007002" class="text-orange decor-db text-lg font-inter hover:underline phone">
                    +9989 71 200 70 02
                </a> 
                <div class="text-gray d-flex justify-center align-center gap-1 cursor-pointer font-inter">
                    <span>Рус</span>
                    <img src="@/assets/icons/arrow.svg" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
@import '@/styles/layouts/header.scss'
</style>