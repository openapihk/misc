<link rel="stylesheet" href="https://unpkg.com/swagger-ui-dist@4.5.0/swagger-ui.css" />
<script src="https://unpkg.com/swagger-ui-dist@4.5.0/swagger-ui-bundle.js" crossorigin></script>
<script src="https://unpkg.com/swagger-ui-dist@4.5.0/swagger-ui-standalone-preset.js" crossorigin></script>

<script>
  window.onload = () => {
    window.ui = SwaggerUIBundle({
      url: 'https://raw.githubusercontent.com/openapihk/hospital_authority/main/aedwt.yaml',
      dom_id: '#swagger-ui-aedwt',
    });    
  };
</script>

<div id="swagger-ui-aedwt"></div>
