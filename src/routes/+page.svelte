<div class="flex flex-col items-center justify-center h-full">
	<h1><span class="gradient-heading">Welcome!</span></h1>
	<h3>
		<span class="bg-gradient-to-br from-blue-500 to-cyan-300 bg-clip-text text-transparent box-decoration-clone">This is a site with few basic pages</span>
	</h3>
	<div class="mt-12 flex flex-col flex-wrap md:flex-row items-center justify-center">
		<a href="/" class="btn variant-filled-primary m-4" data-sveltekit-preload-data="hover">Assignment 1</a>
		<a href="/" class="btn variant-filled-primary m-4" data-sveltekit-preload-data="hover">Assignment 2</a>
		<a href="/assignment/three" class="btn variant-filled-primary m-4" data-sveltekit-preload-data="hover">Assignment 3</a>
		<a href="/assignment/four" class="btn variant-filled-primary m-4" data-sveltekit-preload-data="hover">Assignment 4</a>
		<a href="/assignment/five" class="btn variant-filled-primary m-4" data-sveltekit-preload-data="hover">Assignment 5</a>
		<a href="/assignment/six" class="btn variant-filled-primary m-4" data-sveltekit-preload-data="hover">Assignment 6</a>
	</div>
</div>

<style>
	.gradient-heading {
		@apply bg-clip-text text-transparent box-decoration-clone;
		/* Direction */
		@apply bg-gradient-to-br;
		/* Color Stops */
		@apply from-primary-500 via-tertiary-500 to-secondary-500;
	}
</style>