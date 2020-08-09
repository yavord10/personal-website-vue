<template>
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="carouselIndicator active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1" class="carouselIndicator"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2" class="carouselIndicator"></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <div class="carousel-image-container mx-auto"><img class="d-block w-100" :src="img" alt="First slide"></div>
            </div>
            <div class="carousel-item">
                <div class="carousel-image-container mx-auto"><img class="d-block w-100" :src="img" alt="First slide"></div>
            </div>
            <div class="carousel-item">
                <div class="carousel-image-container mx-auto"><img class="d-block w-100" :src="img" alt="First slide"></div>
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>
</template>

<script>
import img from '../assets/logo.png'

export default {
    name: 'PortfolioSlider',
    data: () => {
        return {
            img: img
        }
    }
}
</script>

<style>
#carouselExampleIndicators {
    background-color: lightblue;
}

.carousel-image-container {
    width: 20%;
    align-self: center;
}

.carouselIndicator {
    background-color: gray !important;
}
.carouselIndicator.active {
    background-color: green !important;
}

</style>