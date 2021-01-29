<template>
  <div>
    <div class="container mx-auto">
      <h1 class="title">
        Carousel
      </h1>
    </div>

    <div>
    <ListImage></ListImage>
    </div>
  </div>
</template>

<script>
import ListImage from "@/components/ListImage";

export default {
  components: ListImage
}

</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  display: flex;
  justify-content:center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

</style>
