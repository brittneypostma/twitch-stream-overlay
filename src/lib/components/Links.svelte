<footer>
	<img class="bg" src="bg.png" alt="Brittney Postma on a wave" />
	<section>
		<a href="brittneypostma.com">
			<img src="logo.png" alt="b in a wave shape" />
			BrittneyPostma.com
		</a>
		<a href="codingcat.dev">
			<img src="coding-cat.png" alt="Black cat with a rainbow tag with AJ on it" />
			CodingCat.dev
		</a>
		<a href="github.com/brittneypostma">
			<img src="github.png" alt="github logo on a palm leaf" />
			Github.com/BrittneyPostma
		</a>
		<a href="twitter.com/brittneypostma">
			<img src="twitter.png" alt="Twitter logo on a palm leaf" />
			Twitter.com/BrittneyPostma
		</a>
	</section>
</footer>

<style>
	section {
		display: grid;
		justify-items: start;
		position: absolute;
		bottom: 0;
		left: 0;
		padding: 0 0 1rem 10rem;
	}

	.bg {
		position: absolute;
		bottom: 0;
		left: 0;
		width: 300px;
		z-index: -1;
	}

	a {
		display: flex;
		gap: 0.5rem;
		align-items: center;
		justify-content: center;
	}
	a:hover {
		border-bottom: none;
	}
	img {
		width: 30px;
		display: grid;
		align-items: center;
		justify-content: center;
	}
</style>
