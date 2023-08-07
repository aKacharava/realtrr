<template>
    <Link href="/">Index page</Link>&nbsp;
    <Link href="/hello">Show page</Link>
    <div v-if="flashSuccess" class="success">
        {{ flashSuccess }}
    </div>
    <slot></slot>
</template>

<script setup>
import { computed } from "vue";
import { Link, usePage } from "@inertiajs/vue3";

const flashSuccess = computed(() => usePage().props.flash.success);
</script>

<style scoped>
.success {
    background: purple;
    color: white;
}
</style>
