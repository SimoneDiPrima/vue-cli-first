<template>
  <div id="app">
    <img src="https://i.picsum.photos/id/1010/5184/3456.jpg?hmac=7SE0MNAloXpJXDxio2nvoshUx9roGIJ_5pZej6qdxXs" alt="">
    <figcaption><strong>e c è anche un immagine!</strong></figcaption>
  </div>
</template>

<script>
export default {
  name: `JumbotronComponent`
}

</script>

<style>
figcaption {
    font-size: 2rem;
     position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    color:goldenrod;
}
img{
    max-width:100%;
    height:100vh;
}
</style>