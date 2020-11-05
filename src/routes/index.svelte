<svelte:head>
	<title>Hasyir.com</title>
</svelte:head>

<div class="container-sm">
  <p>
  <h5 class="text-center">Hasyir Adzra Nalendra</h5>
  <div class='text-center'><small>I was born { age }</small></div>

  <p>

  <div class="container">
    <div class="row">
      <div class="col-sm">
        <img src="http://res.cloudinary.com/nusendra/image/upload/v1604561732/hasyir/565D87B9-833C-4554-AB39-F4AA672AF633_ggalom.jpg" class="rounded mx-auto d-block" width="100%" alt="hasyir domblong">
      </div>
      <div class="col-sm">
        <img src="https://res.cloudinary.com/nusendra/image/upload/v1604571793/hasyir/4B0C8C4F-CD8D-48A6-BC61-FA85ECF08A96_lvyxol.jpg" class="rounded mx-auto d-block" width="100%" alt="hasyir senyum">
      </div>
      <div class="col-sm">
        <img src="https://res.cloudinary.com/nusendra/image/upload/v1604571781/hasyir/6FEAF705-BE8B-41D4-8BD1-8A8ACD165C99_ycpbug.jpg" class="rounded mx-auto d-block" width="100%" alt="hasyir sepeda">
      </div>
    </div>
  </div>
</div>

<script>
  import { formatDistanceToNow  } from 'date-fns'

  let age = formatDistanceToNow(new Date(2019, 8, 29), { addSuffix: true })
</script>
