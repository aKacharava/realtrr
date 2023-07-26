<template>
    <Link href="/">Index page</Link>&nbsp;
    <Link href="/hello">Show page</Link>
    <slot></slot>
</template>

<script setup>
import { Link } from "@inertiajs/vue3";
</script>
