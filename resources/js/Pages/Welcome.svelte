<script>
    import { page } from '@inertiajs/svelte'
</script>
<div class="flex flex-col gap-4 w-dvw h-dvh justify-center items-center">
    <h1 class="text-2xl font-bold">Hello, world!</h1>
    <h2>From <strong class="text-primary">{$page.component}</strong> component</h2>
</div>
