<script lang="ts">
import { SvelteDate } from 'svelte/reactivity'
    const year = new SvelteDate().getFullYear();
</script>

<footer class='flex justify-center items-center p-6'>
    <p>&copy; {year} Horace Boston III. Made by hand with love.</p>
</footer>