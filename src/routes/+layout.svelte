<script>
	import Header from './Header.svelte';
	import '../app.css';
	import Footer from './Footer.svelte';
</script>

<div class="bg-dark-900 text-light-50 min-h-screen">
	<Header />
<main class='px-6  sm:px-12 md:px-16 lg:px-36 w-full flex justify-center py-6'>
	<main class='w-full grid lg:grid-cols-5 grid-cols-1 max-w-7xl  justify-center '>
		<aside class='w-full rounded p-3 border border-dark-700 bg-dark-800 h-full '>d</aside>
		<section class='lg:col-span-3 h-[800px]'>
			<slot />
		</section>
		<aside class='w-full rounded p-3 border border-dark-700 bg-dark-800 h-full '>d</aside>
	</main>

</main>

	<Footer />
</div>

