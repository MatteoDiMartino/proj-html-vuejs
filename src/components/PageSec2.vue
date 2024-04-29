<script>

export default {
    name: 'PageSec2'
}

</script>

<template>

<div class="container">
    <div class="row">
        <div class="ms-box-txt text-center">
            <div class="fw-bold fs-3">Our Professional Cycling Trainings</div>
        </div>
        <small class="text-center">Learn from the mountain biking expert.</small>
    </div>

    <div class="d-flex text-center justify-content-center">
        <div class="col d-flex text-center justify-content-center">
            <div class="ms-card-box">
                <img src="../assets/img/training-box-1.jpg" alt="">
            </div>
        </div>
        <div class="col d-flex text-center justify-content-center">
            <div class="ms-card-box">
                <img src="../assets/img/training-box-1.jpg" alt="">
            </div>
        </div>
        <div class="col d-flex text-center justify-content-center">
            <div class="ms-card-box">
                <img src="../assets/img/training-box-1.jpg" alt="">
            </div>
        </div>
        <div class="col d-flex text-center justify-content-center">
            <div class="ms-card-box">
                <img src="../assets/img/training-box-1.jpg" alt="">
            </div>
        </div>
    </div>
</div>

</template>

<style scoped lang="scss">

.ms-card-box {
    margin-top: 20px;
    border: 10px solid black;
    height: 480px;
    width: 270px;

    col {
        display: flex;
        justify-content: center;
    }

    img {
        height: 100%;
        width: 100%;
        object-fit: cover;
    }
}

</style>