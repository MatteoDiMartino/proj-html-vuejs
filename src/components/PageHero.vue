<script>

export default {
    name: 'PageHero'
}

</script>

<template>

<section>
    <img src="../assets/img/event3.jpg" alt="" class="ms-scroll-img">
    <div class="container">
        <div class="ms-box-hero">
            <div class="ms-box-txt text-white">
                        <div class="col d-flex align-items-center m-5">
                            <div class="ms-box-btn me-3">
                                <button>
                                    <i class="fa-solid fa-chevron-left"></i>
                                </button>
                            </div>
                            <div class="justify-content-start">
                                    <div class="fs-1 fw-bold w-50 ms-maintxt-slider mb-2">Professional Cycling Club</div>
                                <span class="pt-1">Learn cycling from the pros.</span>
                                <div class="mt-3">
                                    <button class="ms-slider-btn mb-5 bg-black text-white py-3 px-5">
                                        <span>Learn More</span>
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="col-1">
                        <div class="m-5">
                            <div class="ms-box-btn">
                                <button>
                                    <i class="fa-solid fa-angle-right"></i>                         
                                </button>
                            </div>
                        </div>
                </div>    
            </div>
        </div>
    </div>


</section>

</template>

<style scoped lang="scss">

section {
    height: 550px;

    .ms-scroll-img {
        width: 100%;
        height: 100%;
        object-fit: cover;
    }

    .ms-box-btn {
        width: 40px;
        height: 40px;
        background-color: black;
        display: flex;
        justify-content: center;
        border-radius: 5px;

        button {
            font-size: 21px;
            color: white;
            background-color: transparent;
        }
    }

    .ms-box-hero {
        display: flex;
        justify-content: center;

        button {
            transition: 0.3s;
            border-radius: 10px;
            border: 0;

            &:hover {
                transition: 0.6s;
                font-size: 20px;
                border-radius: 10px;  
                box-shadow: rgba(50, 50, 93, 0.25) 0px 2px 5px -1px, rgba(0, 0, 0, 0.3) 0px 1px 3px -1px;              
            }
        }
    } 
}

.ms-box-txt {
    position: absolute;
    bottom: 0;
    top: 0;
    display: flex; 
    align-items: center;
    justify-content: center;
    width: 100%;
}

.ms-maintxt-slider {
    line-height: 45px;
}



</style>