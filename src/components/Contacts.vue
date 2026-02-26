<template>
    <section id="contacts" class="bg-[rgba(184,156,125,0.2)]">
        <div class="w-[350px] bg-accent text-white mx-auto! px-6 py-4 rounded contacts-info">
            <h3 class="uppercase bold text-2xl mb-4!">Contact me:</h3>
            <ul>
                <li><a href="tel:+32476029813" class="flex items-center gap-2 contact-link"><svg
                            xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" width="16" height="16"
                            fill="white">
                            <path
                                d="M160.2 25C152.3 6.1 131.7-3.9 112.1 1.4l-5.5 1.5c-64.6 17.6-119.8 80.2-103.7 156.4 37.1 175 174.8 312.7 349.8 349.8 76.3 16.2 138.8-39.1 156.4-103.7l1.5-5.5c5.4-19.7-4.7-40.3-23.5-48.1l-97.3-40.5c-16.5-6.9-35.6-2.1-47 11.8l-38.6 47.2C233.9 335.4 177.3 277 144.8 205.3L189 169.3c13.9-11.3 18.6-30.4 11.8-47L160.2 25z" />
                        </svg>0476029813</a></li>
                <li><a href="mailto:kseniyamesch0101@gmail.com" class="flex items-center gap-2 contact-link"><i
                            class="fas fa-envelope"></i> kseniyamesch0101@gmail.com</a></li>
                <li><a href="https://github.com/kseniyamesch" rel="noopener noreferrer" target="_blank"
                        class="flex items-center gap-2 contact-link"><i class="fab fa-github"></i> GitHub</a></li>
                <li><a href="https://www.linkedin.com/in/kseniia-malyshenko/" rel="noopener noreferrer" target="_blank"
                        class="flex items-center gap-2 contact-link"><i class="fab fa-linkedin"></i> LinkedIn</a></li>
            </ul>
        </div>
    </section>
</template>

<script setup lang="ts">

</script>

<style scoped>
@media screen and (max-width: 429px) {
    .contacts-info {
        width: 300px;
    }
}

.contact-link {
    transition: transform 500ms linear;
}

.contact-link:hover {
    transform: translateY(-2px) scale(1.05);
}
</style>