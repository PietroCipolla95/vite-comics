<script>
export default {

    name: 'AppComics',

    props: {
        series: String,
        thumb: String,
    }

}
</script>


<template>
    <div class="card bg-transparent border-0">
        <div class="comics_img">
            <img :src="thumb">
        </div>
        <div class="comic_title pt-2">
            <p class="text-light">
                {{ series }}
            </p>
        </div>
    </div>
</template>


<style lang="scss" scoped>
img {
    max-width: 100%;
    height: 260px;
    aspect-ratio: 1/1;
    object-fit: cover;
}
</style>