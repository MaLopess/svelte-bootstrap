<script>
	export let color;
    export let outline;
	
	function getClass(prefix, suffix) {
		if(!suffix) {
        
			return '';
            
		}
        if(outline) {
            return `${prefix}-outline-${suffix}`;  
        }
		return `${prefix}-${suffix}`;
        
	}
</script>


<button type="button" class="btn {getClass('btn', color)}">
	<slot /> class="btn {getClass('btn', color)}"
</button>