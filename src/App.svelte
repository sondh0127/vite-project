<script lang="ts">
	import TopIcons from './components/TopIcons.svelte'
</script>

<main class="flex justify-center">
	<div
		class="relative w-[350px] h-[712px] rounded-[60px] shadow-xl bg-black overflow-hidden border-[14px] border-black"
	>
		<img
			src="https://wallpapers.hector.me/wavey/Rainbow%20iPhone%20P3.jpg"
			alt="iphone bg"
			class="absolute inset-0 w-full h-full object-cover "
		/>
		<div class="absolute top-0 inset-x-0">
			<div class="h-6 w-40 mx-auto bg-black rounded-b-3xl" />
		</div>
		<div class="relative">
			<TopIcons />
			<div class="bg-white h-0.5 w-10 mr-7 ml-auto mt-1.5 rounded" />

			<div class="mt-2 flex flex-col items-center">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					class="h-8 w-8 text-white"
					viewBox="0 0 20 20"
					fill="currentColor"
				>
					<path
						d="M10 2a5 5 0 00-5 5v2a2 2 0 00-2 2v5a2 2 0 002 2h10a2 2 0 002-2v-5a2 2 0 00-2-2H7V7a3 3 0 015.905-.75 1 1 0 001.937-.5A5.002 5.002 0 0010 2z"
					/>
				</svg>
				<p class="mt-3 text-white text-6xl font-extralight">9:41</p>
				<p class="mt-1 text-white text-lg font-light">Monday, June 7</p>
			</div>

			<div class="mt-4 mx-2 relative">
				<div
					class="absolute -bottom-4 transform scale-85 origin-bottom inset-x-0 h-full w-full bg-white/10  backdrop-filter backdrop-blur-md rounded-2xl"
				/>
				<div
					class="absolute -bottom-2 transform scale-95 origin-bottom inset-x-0 h-full w-full bg-white/30 backdrop-filter backdrop-blur-md rounded-3xl shadow-sm"
				/>

				<div
					class="p-4 backdrop-filter backdrop-blur-md bg-white/40 rounded-3xl shadow"
				>
					<div class="flex justify-between">
						<div>
							<p class="text-xs font-bold">9:30 AM</p>
							<h2 class="text-lg font-bold">Your Morning Summary</h2>
						</div>
						<span
							class="rounded-full bg-gray-500 h-8 w-8 flex items-center justify-center text-white"
						>
							11
						</span>
					</div>
					<div class="mt-2 grid grid-cols-2 gap-2">
						<div>
							<img
								class="rounded-lg"
								src="https://images.unsplash.com/photo-1588974269162-4c0d5ccc6094?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=3302&q=80"
								alt="Surfer at sunset"
							/>
							<h3 class="mt-2 text-xs font-bold leading-tight">
								Surfing: heals the soul, kills the ribs
							</h3>
							<p class="mt-1 text-xs">
								It's all fun and thrills until you get sucked over the falls.
							</p>
						</div>
						<div>
							<img
								class="rounded-lg"
								src="https://images.unsplash.com/photo-1588974269162-4c0d5ccc6094?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=3302&q=80"
								alt="Surfer at sunset"
							/>
							<h3 class="mt-2 text-xs font-bold leading-tight">
								The NBA Finals are here!
							</h3>
							<p class="mt-1 text-xs">
								Bucks vs Suns is shaping up to be a very intriguing series!
							</p>
						</div>
					</div>
					<hr class="mt-4 border-black/20" />
					<div class="mt-3 grid grid-cols-3 gap-1 items-end">
						<div class="col-span-2">
							<h3 class="font-bold text-xs">More Updates</h3>
							<p class="mt-0.5 text-xs">
								Polywork, Keystone 6, and Sarah Drasner
							</p>
							<p />
						</div>
						<ul class="flex -space-x-4 flex-row-reverse space-x-reverse">
							<li>
								<img
									class="w-8 h-8 rounded-lg object-cover"
									src="https://seeklogo.com/images/K/keystonejs-logo-C77FDB0662-seeklogo.com.png"
									alt="1"
								/>
							</li>
							<li>
								<img
									class="w-8 h-8 rounded-lg object-cover"
									src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQEZUAlsS1loKxsx8abFEgwSi5KBus3tmsQaA&usqp=CAU"
									alt="2"
								/>
							</li>
							<li>
								<img
									class="w-8 h-8 rounded-lg object-cover"
									src="https://www.engmanagement.dev/_next/image?url=%2F_next%2Fstatic%2Fimage%2Fpublic%2Fimages%2Fsarah-drasner%402x.fa3f0a5d32f918fbe0918080d2767ad7.jpg&w=384&q=95"
									alt="3"
								/>
							</li>
						</ul>
					</div>
				</div>
			</div>
		</div>

		<!-- Flashlight, camera and bottom swipe menu -->
		<div class="absolute bottom-0 inset-x-0 h-20">
			<div class="px-10 flex justify-between">
				<button
					class="bg-gray-800/40 backdrop-blur-md text-white rounded-full p-2"
				>
					<svg
						xmlns="http://www.w3.org/2000/svg"
						class="h-6 w-6"
						viewBox="0 0 20 20"
						fill="currentColor"
					>
						<path
							d="M11 3a1 1 0 10-2 0v1a1 1 0 102 0V3zM15.657 5.757a1 1 0 00-1.414-1.414l-.707.707a1 1 0 001.414 1.414l.707-.707zM18 10a1 1 0 01-1 1h-1a1 1 0 110-2h1a1 1 0 011 1zM5.05 6.464A1 1 0 106.464 5.05l-.707-.707a1 1 0 00-1.414 1.414l.707.707zM5 10a1 1 0 01-1 1H3a1 1 0 110-2h1a1 1 0 011 1zM8 16v-1h4v1a2 2 0 11-4 0zM12 14c.015-.34.208-.646.477-.859a4 4 0 10-4.954 0c.27.213.462.519.476.859h4.002z"
						/>
					</svg>
				</button>
				<button
					class="bg-gray-800/40 backdrop-blur-md text-white rounded-full p-2"
				>
					<svg
						xmlns="http://www.w3.org/2000/svg"
						class="h-6 w-6"
						viewBox="0 0 20 20"
						fill="currentColor"
					>
						<path
							fill-rule="evenodd"
							d="M4 5a2 2 0 00-2 2v8a2 2 0 002 2h12a2 2 0 002-2V7a2 2 0 00-2-2h-1.586a1 1 0 01-.707-.293l-1.121-1.121A2 2 0 0011.172 3H8.828a2 2 0 00-1.414.586L6.293 4.707A1 1 0 015.586 5H4zm6 9a3 3 0 100-6 3 3 0 000 6z"
							clip-rule="evenodd"
						/>
					</svg>
				</button>
			</div>
			<div class="absolute bottom-1 inset-x-0">
				<div class="mx-auto h-1 w-28 rounded bg-white" />
			</div>
		</div>
	</div>
</main>

<style>
</style>
