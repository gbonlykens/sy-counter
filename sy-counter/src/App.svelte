<script>
	import Counter from './Counter.svelte'
	</script>
	
	<main>
		<div id="page-container">
		<div class = "header-container">
		<h1>SY Counter</h1>
		</div>
		<Counter />
	</div>
	</main>
	
	
	<style>
	
		#page-container {
			display: flex;
			justify-content: center;
			align-items: center;
		}
	
		.header-container {
			display: flex;
			justify-content: center;
			align-items: center;
		}
	
		h1{
			display: inline-flex;
			justify-content: center;
			align-items: center;
			font-size: 67px;
			letter-spacing: 34px;
			width: 70%;
			height: 20vh;
			color: #31fde2;
			background-color: #007fff;
			border-style: double;
		}
	
	</style>
	
	