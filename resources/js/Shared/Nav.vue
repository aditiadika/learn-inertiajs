<template>
    <nav>
        <ul class="li"><Link href="/">Home</Link></ul>
        <ul class="li"><Link href="/users">Users</Link></ul>
        <ul class="li"><Link href="/settings">Settings</Link></ul>
    </nav>
</template>

<script>
    import { Link } from '@inertiajs/inertia-vue3';

    export default{
        components: { Link },
        props:{}
    }
</script>