<script>

export default {
    name: 'PageHero'
}

</script>

<template>

<section>
    <div class="container">
        <div class="ms-box-hero d-flex">
            <button class="border-0 px-2 py-1 bg-black text-white fs-4">
                <i class="fa-solid fa-arrow-left"></i>
            </button>
            <div class="text-white p-5">
                <div class="fs-1 fw-bold w-50 ms-maintxt-slider mb-2">Professional Cycling Club</div>
                <span class="pt-1">Learn cycling from the pros.</span>
                <div class="mt-3">
                    <button class="ms-slider-btn mb-5 bg-black border-0 text-white py-3 px-5">Learn More</button>
                </div>
            </div>
         <div class="col">
            <div class="d-flex justify-content-end">
                <button class="border-0 px-2 py-1 bg-black text-white fs-4">
                    <i class="fa-solid fa-arrow-right"></i>
                </button>
            </div>
         </div>

        </div>
    </div>
</section>

</template>

<style scoped lang="scss">

section {
    background-image: url(../assets/img/event3.jpg);
    background-size: cover;

    .ms-box-hero {
        object-fit: cover;
        height: 600px;
        justify-content: start;
        align-items: center;
    } 
}

.ms-maintxt-slider {
    line-height: 45px;
}



</style>