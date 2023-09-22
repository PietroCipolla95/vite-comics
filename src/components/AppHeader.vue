<script>

export default {
    name: 'AppHeader',
}




</script>

<template>
    <header>
        <nav class="navbar navbar-expand navbar-light p-0 bg-body d-flex justify-content-between my_container">
            <!-- nav logo -->
            <div class="py-4">
                <img src="../assets/img/dc-logo.png" alt="" srcset="">
            </div>
            <!-- nav links -->
            <div class="nav navbar-nav">
                <a class="nav-item nav-link" href="#">CHARACTERS</a>
                <a class="nav-item nav-link" href="#">COMICS</a>
                <a class="nav-item nav-link" href="#">MOVIES</a>
                <a class="nav-item nav-link" href="#">TV</a>
                <a class="nav-item nav-link" href="#">GAMES</a>
                <a class="nav-item nav-link" href="#">COLLECTIBLES</a>
                <a class="nav-item nav-link" href="#">VIDEOS</a>
                <a class="nav-item nav-link" href="#">FANS</a>
                <a class="nav-item nav-link" href="#">NEWS</a>
                <a class="nav-item nav-link" href="#">SHOP</a>
            </div>
        </nav>
    </header>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

a {
    margin-left: 1rem;
    font-weight: 700;

    &:hover {
        color: $dc-primary;

        border-bottom: 1px solid aqua;
    }

}
</style>
