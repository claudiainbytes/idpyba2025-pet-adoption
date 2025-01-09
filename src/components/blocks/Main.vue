<script setup lang="ts">
import Intro from './../../components/blockComponents/Intro.vue'
import Card from './../../components/blockComponents/Card.vue'
</script>

<template>
    <main>
        <Intro/>
            <div class="album py-5 bg-body-tertiary">
            <div class="container">

                <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 g-3">
                <div class="col">
                    <Card/>
                </div>
                <div class="col">
                    <Card/>
                </div>
                <div class="col">
                    <Card/>
                </div>

                <div class="col">
                    <Card/>
                </div>
                <div class="col">
                    <Card/>
                </div>
                <div class="col">
                    <Card/>
                </div>

                <div class="col">
                    <Card/>
                </div>
                <div class="col">
                    <Card/>
                </div>
                <div class="col">
                    <Card/>
                </div>
                </div>
            </div>
            </div>
    </main>
</template>

<style scoped>
</style>
