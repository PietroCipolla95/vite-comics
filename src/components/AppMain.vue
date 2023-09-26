<script>
import comics from '../comics.js';

import AppJumbotron from './AppJumbotron.vue';

import AppComicsCard from './AppComicsCard.vue';



export default {
    name: 'AppMain',

    data() {
        return {
            comics
        }
    },

    components: {
        AppJumbotron,
        AppComicsCard
    }

}

</script>


<template>
    <main>
        <AppJumbotron />

        <div class="comics_sec">
            <!-- cards row -->
            <div class="row py-5 my_container">
                <!-- current series hover -->
                <div class="current_series position-relative">
                    <div class="bg-dc px-3 py-2 my_btn_abs rounded-0 px-4 text-light">
                        <h5 class="fs-4">
                            CURRENT SERIES
                        </h5>
                    </div>
                </div>

                <div class="col-2 mb-3" v-for="comic in comics">

                    <AppComicsCard :thumb="comic.thumb" :series="comic.series.toUpperCase()"></AppComicsCard>

                </div>
            </div>

            <div class="col-2 d-flex m-auto py-3">
                <button class="btn bg-dc rounded-0 px-4 py-2 text-light fw-bolder">
                    LOAD MORE
                </button>
            </div>

        </div>


    </main>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.comics_sec {
    background-color: rgb(46, 42, 42);

    .my_btn_abs {
        position: absolute;
        top: -4.5rem;
        left: -1rem;
    }

    .bg-dc {
        background-color: $dc-primary;
    }



}
</style>