<template>
    <div class="flex">
        <div class="nav-start">
            left
        </div>
        <div class="nav-center">
            center
        </div>
        <div class="nav-end">
            right
        </div>
    </div>
</template>

<style scoped>
.nav-start {
    @apply w-1/4 flex;
}

.nav-center {
    @apply w-2/4 flex;
}

.nav-end {
    @apply w-1/4 flex;
}
</style>