<script lang="ts">
	import { ModeWatcher } from 'mode-watcher';
	import '../app.css';
	import SiteHeader  from '../lib/components/site-header/+page.svelte';
	let { children } = $props();
</script>

<ModeWatcher />

<SiteHeader />
{@render children()}
