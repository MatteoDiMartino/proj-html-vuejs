<script>

export default {
    name: 'PageSec1'
}

</script>

<template>


<section>
    <div class="container">
        <div class="row">
            <div class="col-6">
                <img src="../assets/img/bike-player.png" class="w-75 my-5 ms-img-bg">
            </div>
            <div class="col-6">
                <div class="w-75 my-5">
                    <div class="ms-h fs-2 fw-bold w-75">
                        Do you want to be a professional cyclist?            
                    </div>
                    <div class="fw-light ms-p">
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Aliquam quod sunt, cumque temporibus aliquid fugiat ducimus similique ex quis architecto totam quidem recusandae, eum at pariatur! A doloremque unde dolores.</p>
                    </div>
                    <img src="../assets/img/divider.jpg" alt="">

                    <div class="row">
                        <div class="ms-box-icon">
                            <div class="col d-flex align-items-center">
                                <img src="../assets/img/racing-helmet.png" alt="" class="ms-icon">
                                <div class="mx-4"> 
                                    <div class="fs-4 fw-bold d-flex">
                                        <span class="align-items-start">Professional Team</span>
                                    </div>
                                    <span>We make you professional by adding your sincerity as well as professionalism.</span>
                                </div>
                            </div>
                            
                            <div class="col d-flex align-items-center h-25">
                                <img src="../assets/img/helmet.png" alt="" class="ms-icon">
                                <div class="mx-4"> 
                                    <div class="fs-4 fw-bold d-flex">
                                        <span class="align-items-start">Professional Trainings</span>
                                    </div>
                                    <span>We make you professional by adding your sincerity as well as professionalism.</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>


</template>

<style scoped lang="scss">

.ms-img-bg {
    background-image: url(../assets/img/bike-circle.png);
    background-size: contain;
    background-repeat: no-repeat;
}

.ms-h {
    line-height: 40px;
}

.ms-p {
    margin-top: 10px;
    font-size: 17px;
}

.ms-icon {
    margin: 40px 0px;
    width: 65px;
}

</style>