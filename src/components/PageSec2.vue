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
                <div class="box-txt">
                    <span class="ms-card-txt fw-bold fs-5 text-white ">Riding Lesson</span>  
                </div>
                <img src="../assets/img/training-box-1.jpg" alt="" class="">
            </div>
        </div>
        <div class="col d-flex text-center justify-content-center">
            <div class="ms-card-box">
                <div class="box-txt">
                    <span class="ms-card-txt fw-bold fs-5 text-white ">Safe Driving</span>  
                </div>
                <img src="../assets/img/training-box-2.jpg" alt="">
            </div>
        </div>
        <div class="col d-flex text-center justify-content-center">
            <div class="ms-card-box">
                <div class="box-txt">
                    <span class="ms-card-txt fw-bold fs-5 text-white ">Mountain Bike</span>  
                </div>
                <img src="../assets/img/training-box-3.jpg" alt="">
            </div>
        </div>
        <div class="col d-flex text-center justify-content-center">
            <div class="ms-card-box">
                <div class="box-txt">
                    <span class="ms-card-txt fw-bold fs-5 text-white ">Trail Drive</span>  
                </div>
                <img src="../assets/img/training-box-4.jpg" alt="">
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
    background-color: black;

    col {
        display: flex;
        justify-content: center;
    }

    img {
        height: 100%;
        width: 100%;
        object-fit: cover;
        opacity: 0.7;
        transition: 0.7s;

        &:hover {
            opacity: 1;
            transition: 1s;
        }
    }

    .box-txt {
        position: relative;
        span {
            position: absolute;
            top: 0;
            left: 0;
            padding: 10px 20px;
        }
    }
}

</style>