<script lang="ts">
	let title = 'Nice title';

	function updateTitle(): void {
		title = 'Another awesome title';
	}
</script>

<div class="index">
	<h2>{title}</h2>

	<p>
		Lorem ipsum d sit ameeeeeeeeeeeeet consectetur adipisicing elit. Aliquam atque excepturi
		aspernatur autem nihil impedit voluptate, vitae dolorum corporis sed nisi, nemo nam sit enim eum
		minima hic animi obcaecati?
	</p>

	<button on:click={updateTitle}>UPDATE DAMN TITLE</button>

	<input type="text" bind:value={title} />
</div>

<style lang="sass">

    .index
        max-width: 50vh
        text-align: center
        margin: 20px auto

</style>
