<style>
	h1, h2, figure, p {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 2.8em;
		text-transform: uppercase;
		font-weight: 700;
		margin: 0 0 0.5em 0;
	}

	figure {
		margin: 0 0 1em 0;
	}

	img {
		width: 100%;
		max-width: 400px;
		margin: 0 0 1em 0;
	}

	p {
		margin: 1em auto;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>

<svelte:head>
	<title>Hasyir.com</title>
</svelte:head>

<h1>Hi world, my name is Hasyir!</h1>
<h2>I was born { age }</h2>

<script>
  import { formatDistanceToNow  } from 'date-fns'

  // Month start from 0
  let age = formatDistanceToNow(new Date(2019, 8, 29), { addSuffix: true })
</script>
