<script>
import AppJumbotron from './AppJumbotron.vue';
import AppComics from './AppComics.vue';


export default {
    name: 'AppMain',

    components: {
        AppJumbotron,
        AppComics
    }

}

</script>


<template>
    <main>
        <AppJumbotron></AppJumbotron>
        <AppComics></AppComics>

    </main>
</template>


<style lang="scss" scoped></style>