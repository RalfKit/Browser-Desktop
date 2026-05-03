<script lang="ts">
	let { open = $bindable(true) }: { open: boolean } = $props();

	function closeDialog() {
		open = false;
	}
</script>

<dialog id="demo" class="modal z-9910" {open}>
	<div class="modal-box max-w-1/3 min-w-5/6 md:min-w-2xl">
		<h3 class="text-lg font-bold">Browser-Desktop Demo</h3>
		<p class="py-4">
			You are currently using an early demo version of <strong>Browser-Desktop</strong>.<br />
			The system is still under active development.<br />
			Many features such as window management, and taskbar are already functional — but many more are
			coming soon!<br />
			<a
				href="https://github.com/RalfKit/browser-desktop"
				class="link-primary link"
				target="_blank"
				rel="noopener noreferrer"
			>
				GitHub Repository
			</a>
		</p>
		<div class="modal-action">
			<button class="btn" onclick={closeDialog}>Close Window</button>
		</div>
	</div>
</dialog>
