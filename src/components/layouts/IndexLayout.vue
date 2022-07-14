
<template>
    <div class="min-h-full">
        <TheNavigationVue />
        <div class="py-10">
            <main>
                <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
                    <!-- Replace with your content -->
                    <router-view></router-view>
                    <!-- /End replace -->
                </div>
            </main>
        </div>
    </div>
</template>

<script setup>
import TheNavigationVue from '../includes/TheNavigation.vue';
</script>