<script>
	let count = 0;

	function handleClick() {
	  count += 1;
	}
</script>

<style>
	button {
	  background: #6b3410;
	  color: white;
	  border: none;
	  padding: 8px 12px;
	  border-radius: 100px;
	}
</style>

<button on:click={handleClick}>
  Clicked {count} {count === 1 ? 'time' : 'times'}
</button>