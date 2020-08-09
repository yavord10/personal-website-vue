<template>
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="carouselIndicator active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1" class="carouselIndicator"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2" class="carouselIndicator"></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <div class="carousel-image-container row mx-auto">
                    <div class="card col mr-5" style="width: 18rem;">
                        <img class="card-img-top" :src="img" alt="Card image cap">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                            <a href="#" class="btn btn-primary">Go somewhere</a>
                        </div>
                    </div>
                    <div class="card col" style="width: 18rem;">
                        <img class="card-img-top" :src="img" alt="Card image cap">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                            <a href="#" class="btn btn-primary">Go somewhere</a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="carousel-item">
                <div class="carousel-image-container row mx-auto">
                    <div class="card col mr-5" style="width: 18rem;">
                        <img class="card-img-top" :src="img" alt="Card image cap">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                            <a href="#" class="btn btn-primary">Go somewhere</a>
                        </div>
                    </div>
                    <div class="card col mx-auto" style="width: 18rem;">
                        <img class="card-img-top" :src="img" alt="Card image cap">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                            <a href="#" class="btn btn-primary">Go somewhere</a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="carousel-item">
                <div class="carousel-image-container row mx-auto">
                    <div class="card col mr-5" style="width: 18rem;">
                        <img class="card-img-top" :src="img" alt="Card image cap">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                            <a href="#" class="btn btn-primary">Go somewhere</a>
                        </div>
                    </div>
                    <div class="card col mx-auto" style="width: 18rem;">
                        <img class="card-img-top" :src="img" alt="Card image cap">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                            <a href="#" class="btn btn-primary">Go somewhere</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
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
    padding: 50px;
}

.carousel {
    height: 800px;
}

.btn {
    color: white !important;
    background-color: green !important;
}

.carousel-image-container {
    width: 50%;
    align-self: center;
}

.carouselIndicator {
    background-color: gray !important;
}
.carouselIndicator.active {
    background-color: green !important;
}

</style>