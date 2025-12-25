<script setup lang="ts">
    gsap.to('.box', {
        scrollTrigger: '.box',
        x: -300, 
        start: 'top bottom', 
        end: 'bottom top', 
        scrub: 1.5
    });
</script>

<template>
    <div class="box">
        <img src="../../assets/img/scrolling-content.png" />
    </div>
</template>

