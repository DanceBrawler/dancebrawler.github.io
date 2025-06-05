<script>
  const videoId = 'wHe7PtP9Lxk'; // YouTube's official embed test video
</script>

<title>Dance Brawler</title>

<main class="min-h-screen bg-gray-100 flex flex-col items-center justify-center p-4">
	<div class="w-full max-w-3xl">
		<div class="relative w-full pb-[56.25%] h-0">
			<iframe
			class="absolute top-0 left-0 w-full h-full rounded-lg shadow-lg"
			src={`https://www.youtube.com/embed/${videoId}`}
			title="YouTube video player"
			frameborder="0"
			allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
			allowfullscreen
			></iframe>
		</div>
	</div>
</main>