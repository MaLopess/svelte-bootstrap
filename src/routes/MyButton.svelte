<script>
	export let color;
	
	function getClass(prefix, suffix) {
		if(!suffix) {
			return '';
		}
		return `${prefix}-${suffix}`;
	}
</script>


<button type="button" class="btn {getClass('btn', color)}">
	<slot /> class="btn {getClass('btn', color)}"
</button>