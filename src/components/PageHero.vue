<script>

export default {
    name: 'PageHero'
}

</script>

<template>

<section>
    <div class="container">
        <div class="py-4 ms-box-hero">
            <div class="text-white">
                <h1>Professional Cycling Club</h1>
                <span>Learn cycling from the pros.</span>
            </div>
            <button>ciao</button>
        </div>
    </div>
</section>

</template>

<style scoped lang="scss">

section {
    background-image: url(../assets/img/event3.jpg);
    background-size: cover;

    .ms-box-hero {
        height: 600px;
    } 
}

</style>