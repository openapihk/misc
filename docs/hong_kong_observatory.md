<link rel="stylesheet" href="/css/swagger-ui-themes/swagger-ui.css" />
<script src="/js/swagger-ui-bundle.js" crossorigin></script>

<script>
  window.onload = () => {
    window.ui = SwaggerUIBundle({
      url: '[weather](https://raw.githubusercontent.com/openapihk/hong_kong_observatory/main/weather.yaml)',
      dom_id: '#swagger-ui--weather',
    });    
  };
</script>

<div id="swagger-ui-weather"></div>
