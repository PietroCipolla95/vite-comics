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
    <div class="card">
        <div class="comics_img">
            <img :src="thumb">
        </div>
        <div class="comic_title">
            <p>
                {{ series }}
            </p>
        </div>

    </div>
</template>


<style lang="scss" scoped></style>