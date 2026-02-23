<template>
    <section id="projects" class="projects-section">
        <h2 class="hidden">
            Projects
        </h2>
        <ul class="grid gap-5 justify-center [grid-template-columns:repeat(auto-fit,300px)]">
            <li>
                <div class="card">
                    <img src="../assets/barbershop.png" alt="Barbershop project" class="block" width="300px"
                        height="400px">
                    <div class="desc px-6 py-6 text-white">
                        <p>
                            A simple Barber Shop landing page built with HTML, CSS, and minimal JavaScript.

                            Responsive layout – adapts to desktop and mobile screens. Basic animations – smooth
                            transitions
                            for modal and UI elements. Minimalistic and clean design for demonstration purposes.
                        </p>
                        <ul class="flex gap-3 mt-auto! mx-auto!">
                            <li><a href="https://github.com/kseniyamesch/barber-shop" target="_blank"
                                    rel="noopener noreferrer"
                                    class="bg-accent inline-block px-6 py-2 rounded-md">GitHub</a></li>
                            <li><a href="https://kseniyamesch.github.io/barber-shop/" target="_blank"
                                    rel="noopener noreferrer" class="bg-accent inline-block px-6 py-2 rounded-md">Life
                                    page</a></li>
                        </ul>
                    </div>
                </div>

            </li>
            <li>
                <div class="card">
                    <img src="../assets/icecream.png" alt="Icecream project" class="block" width="300px" height="400px">
                    <div class="desc px-6 py-6 text-white">
                        <p>
                            A team-based Ice Cream landing page built with HTML, CSS, and minimal JavaScript.

                            Responsive design for desktop and mobile, smooth UI animations, and a clean, minimalistic
                            layout. Developed collaboratively as part of a team project.
                        </p>
                        <ul class="flex gap-3 mt-auto! mx-auto!">
                            <li><a href="https://github.com/hayhelv/project-ice-cream" target="_blank"
                                    rel="noopener noreferrer"
                                    class="bg-accent inline-block px-6 py-2 rounded-md">GitHub</a></li>
                            <li><a href="https://hayhelv.github.io/project-ice-cream/" target="_blank"
                                    rel="noopener noreferrer" class="bg-accent inline-block px-6 py-2 rounded-md">Life
                                    page</a></li>
                        </ul>
                    </div>
                </div>

            </li>
            <li>
                <div class="card">
                    <img src="../assets/Filmoteka.png" alt="Filmoteka project" class="block" width="300px"
                        height="400px">
                    <div class="desc px-6 py-6 text-white">
                        <p>
                            A team-based movie library web application built with HTML, SCSS, and vanilla JavaScript.

                            Adaptive layout for desktop and mobile, AJAX with external APIs, theme switcher,
                            localStorage, pagination, and search filter. Developed collaboratively as part of a 9-person
                            team, focusing on frontend implementation and feature development.
                        </p>
                        <ul class="flex gap-3 mt-auto! mx-auto!">
                            <li><a href="https://github.com/skochdev/team10-js-project" target="_blank"
                                    rel="noopener noreferrer"
                                    class="bg-accent inline-block px-6 py-2 rounded-md">GitHub</a></li>
                            <li><a href="https://skochdev.github.io/team10-js-project/#" target="_blank"
                                    rel="noopener noreferrer" class="bg-accent inline-block px-6 py-2 rounded-md">Life
                                    page</a></li>
                        </ul>
                    </div>
                </div>
            </li>
            <li>
                <div class="card">
                    <img src="../assets/Finance-Ledger.png" alt="Finance Ledger project" class="block" width="300px"
                        height="400px">
                    <div class="desc px-6 py-6 text-white">
                        <p>
                            An individual finance ledger web application built with HTML and Sass.

                            Responsive layout for desktop and mobile, minimal JavaScript for interactivity, clean and
                            user-friendly design. Focused on semantic markup, modular styles, and adaptive components
                            for an optimal user experience.
                        </p>
                        <ul class="flex gap-3 mt-auto! mx-auto!">
                            <li><a href="https://github.com/kseniyamesch/finance-ledger" target="_blank"
                                    rel="noopener noreferrer"
                                    class="bg-accent inline-block px-6 py-2 rounded-md">GitHub</a></li>
                            <li><a href="https://kseniyamesch.github.io/finance-ledger/" target="_blank"
                                    rel="noopener noreferrer" class="bg-accent inline-block px-6 py-2 rounded-md">Life
                                    page</a></li>
                        </ul>
                    </div>
                </div>
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

    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.35);
}

.desc {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;

    opacity: 0;

    display: flex;
    flex-direction: column;

    transform: translateY(-100%);

    transition: opacity 1000ms ease, transform 500ms ease;
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
    transform: translateY(0);
}
</style>