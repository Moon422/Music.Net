<script setup lang="ts">
import TopBar from '../components/TopBar.vue';
</script>

<template>
    <div class="h-screen">
        <div class="grid grid-rows-[auto_1fr_auto] grid-cols-[14.5rem_1fr] h-full">
            <!-- Topbar -->
            <header class="col-span-2">
                <TopBar />
            </header>

            <!-- Sidebar -->
            <aside class="bg-green-200 overflow-y-auto">
                Sidebar
            </aside>

            <!-- Body (main content area) -->
            <main class="bg-purple-200 overflow-y-auto">
                <div class="h-[1000px]">
                    Body content goes here...
                </div>
            </main>

            <!-- Footer -->
            <footer class="col-span-2 bg-red-200">
                Footer
            </footer>
        </div>
    </div>
</template>