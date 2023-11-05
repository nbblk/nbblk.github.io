<script>
	import '../app.css';
	import { base } from '$app/paths';
</script>

<nav class="w-full h-[50px] p-8 flex justify-center items-center text-lg gap-8">
	<a href="{base}/project">Project</a>
	<a href="{base}/blog">Blog</a>
</nav>

<slot />
