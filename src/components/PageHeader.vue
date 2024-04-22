<script>

export default {
    name: 'PageHeader'
}

</script>

<template>
<header>
    <nav>
    <div class="container">
    <div class="row py-1 px-2">
        <div class="col">
            <img src="../assets/img/logo-gobike.png" alt="logo-gobike" class="w-50">
        </div>
        <div class="col d-flex align-items-center">
            <ul class="d-flex justify-content-center align-items-center">
                <li>
                    <a href="#">Home</a>
                </li>
                
                <li>
                    <a href="#">About Us</a>
                </li>

                <li>
                    <a href="#">Trainings</a>
                </li>

                <li>
                    <a href="#">Packages</a>
                </li>

                <li>
                    <a href="#">Blog</a>
                </li>

                <li>
                    <a href="#">Contact</a>
                </li>
            </ul>
        </div>
        <div class="col">hi</div>
    </div>
</div>

</nav>

</header>

</template>

<style scoped lang="scss">

    ul {
        list-style: none;
        padding: 0;
        margin: 0;

        li {
            width: 102px;
            text-align: center;
        }

        a {
            color: black;
            text-decoration: none;
            font-size: 15px;
        }
    }

</style>