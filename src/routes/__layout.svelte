<script>
    import { Navbar } from 'davjhan-core'
    import 'davjhan-core/src/style.css'
</script>
<style>
    :global(body) {
        overflow: hidden;
        overscroll-behavior: none;
    }
</style>
<div class="container max-w-screen-sm md:border-l md:border-r md:h-screen md:box-content border-gray-100 bg-background">
    <Navbar subPath='Guess the year game'/>
    <slot/>
</div>