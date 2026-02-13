<template>
    <section id="projects" class="px-6 py-4">
        <h2>
            Projects
        </h2>
        <ul class="flex gap-2 justify-center">
            <li>
                <div class="card">
                    <img src="../assets/barbershop.png" alt="Barbershop project" class="block" width="300px"
                        height="400px">
                    <div class="desc px-6 py-6 text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam, aut!</div>
                </div>
                <ul class="flex gap-3">
                    <li><a href="">GitHub</a></li>
                    <li><a href="">Life page</a></li>
                </ul>
            </li>
            <li>
                <div class="card"></div>
            </li>
            <li>
                <div class="card"></div>
            </li>
            <li>
                <div class="card"></div>
            </li>

        </ul>
    </section>

</template>

<script setup lang="ts">

</script>

<style scoped>
.card {
    position: relative;
    width: 300px;
    height: 400px;
    background: orange;
    border-radius: 10px;
    overflow: hidden;
}

.desc {
    position: absolute;
    top: 0;
    left: 0;

    opacity: 0;
}

.card:hover::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(56, 39, 23, 0.9);
}

.card:hover .desc {
    opacity: 1;
}
</style>