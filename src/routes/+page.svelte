<script lang="ts">
	import Button from "../components/Button.svelte";
</script>

<div class="p-2">
	<Button
		onclick={() => {
			alert("This is an alert");
		}}>Alert</Button>
</div>
