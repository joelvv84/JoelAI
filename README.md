<!-- PWA Básico -->
<meta name="theme-color" content="#c026d3"> <!-- color morado neón -->
<link rel="manifest" href="data:application/manifest+json,{
  \"name\": \"Joel AI Desmadre V2\",
  \"short_name\": \"Joel Desmadre\",
  \"start_url\": \".\",
  \"display\": \"standalone\",
  \"background_color\": \"#000000\",
  \"theme_color\": \"#ff3366\",
  \"icons\": [
    {
      \"src\": \"https://via.placeholder.com/192x192/ff3366/000000?text=JD\",
      \"sizes\": \"192x192\",
      \"type\": \"image/png\"
    },
    {
      \"src\": \"https://via.placeholder.com/512x512/ff3366/000000?text=JD\",
      \"sizes\": \"512x512\",
      \"type\": \"image/png\"
    }
  ]
}">
<!-- Para offline básico (opcional) -->
<script>
  if ('serviceWorker' in navigator) {
    navigator.serviceWorker.register('sw.js').catch(console.error);
  }
</script>
