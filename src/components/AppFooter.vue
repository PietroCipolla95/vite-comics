<script>
export default {
    name: 'AppFooter'
}
</script>

<template>
    <section class="main_footer">
        <div class="row my_container">
            <!-- columns on left with all links -->
            <div class="col-5 py-4">
                <div class="row py-4">
                    <!-- dc comics and shop col wrapper -->
                    <div class="col-4">
                        <!-- DC comics section -->
                        <div class="col-12">
                            <h6>
                                DC COMICS
                            </h6>
                            <div class="d-flex flex-column">
                                <a href="#">
                                    Characters
                                </a>
                                <a href="#">
                                    Comics
                                </a>
                                <a href="#">
                                    Movies
                                </a>
                                <a href="#">
                                    TV
                                </a>
                                <a href="#">
                                    Games
                                </a>
                                <a href="#">
                                    Videos
                                </a>
                                <a href="#">
                                    Games
                                </a>
                            </div>
                        </div>
                        <!-- Shop section -->
                        <div class="col-12 pt-4">
                            <h6>
                                SHOP
                            </h6>
                            <div class="d-flex flex-column">
                                <a href="#">
                                    Shop DC
                                </a>
                                <a href="#">
                                    Shop DC Collectibles
                                </a>
                            </div>
                        </div>
                    </div>
                    <!-- Dc section -->
                    <div class="col-4">
                        <h6>
                            DC
                        </h6>
                        <div class="d-flex flex-column">
                            <a href="#">
                                Terms of use
                            </a>
                            <a href="#">
                                Privacy policy (New)
                            </a>
                            <a href="#">
                                Ad Choices
                            </a>
                            <a href="#">
                                Advertising
                            </a>
                            <a href="#">
                                Jobs
                            </a>
                            <a href="#">
                                Subscriptions
                            </a>
                            <a href="#">
                                Talent Workshop
                            </a>
                            <a href="#">
                                CPSC Certificates
                            </a>
                            <a href="#">
                                Ratings
                            </a>
                            <a href="#">
                                Shop Help
                            </a>
                            <a href="#">
                                Contact Us
                            </a>
                        </div>
                    </div>
                    <!-- Sites section -->
                    <div class="col-4">
                        <h6>
                            SITES
                        </h6>
                        <div class="d-flex flex-column">
                            <a href="#">
                                DC
                            </a>
                            <a href="#">
                                MAD Magazine
                            </a>
                            <a href="#">
                                DC Kids
                            </a>
                            <a href="#">
                                DC Universe
                            </a>
                            <a href="#">
                                DC Power Vista
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>



<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.main_footer {
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;

    h6 {
        color: white;
    }

    a {
        text-decoration: none;
        color: grey;
        font-size: .9rem;

        &:hover {
            color: $dc-primary;
        }
    }


}
</style>