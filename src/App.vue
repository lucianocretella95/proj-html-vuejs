<script>
import appmain from './components/appmain.vue';
import Appfooter from './components/Appfooter.vue';
import AppHeader from './components/AppHeader.vue';
import SezioneCards from './components/SezioneCards.vue';
import SezioneGetStarted from './components/SezioneGetStarted.vue';
import SezioneYoutube from './components/SezioneYoutube.vue';
import SezioneSlider from './components/SezioneSlider.vue';
import AppCoursesShop from './components/AppCoursesShop.vue';
export default {
    components: {
        appmain,
        Appfooter,
        AppHeader,
        SezioneCards,
        SezioneGetStarted,
        SezioneYoutube,
        SezioneSlider,
        AppCoursesShop,
    }
}

</script>

<template>
    <div class="menu">
        <div class="item first">
            <span class="label"><i class="fa-regular fa-newspaper"></i></span>
            <span class="tooltip">
                <span class="contenitoreTesto">Select Demo</span>
                <span class="triangle first"></span>
            </span>
        </div>
        <div class="item second">
            <span class="label"><i class="fa-regular fa-comment"></i></span>
            <span class="tooltip">
                <span class="contenitoreTesto">Support Channel</span>
                <span class="triangle second"></span>
            </span>
        </div>
        <div class="item third">
            <span class="label"><i class="fa-regular fa-rectangle-list"></i></span>
            <span class="tooltip">
                <span class="contenitoreTesto">Documentation</span>
                <span class="triangle third"></span>
            </span>
        </div>
        <div class="item fourth">
            <span class="label"><i class="fa-regular fa-credit-card"></i></span>
            <span class="tooltip">
                <span class="contenitoreTesto">Purchase</span>
                <span class="triangle fourth"></span>
            </span>
        </div>
    </div>
    <AppHeader />
    <SezioneCards />
    <SezioneGetStarted />
    <SezioneYoutube />
    <SezioneSlider />
    <AppCoursesShop />
    <appmain />
    <Appfooter />
</template>

<style scoped></style>
