--- 
permalink: /preview-components/dkwds-content.html
layout: base 
title: Dkwds-content.html
---

<!doctype html>
<html lang="en-US">
  <head>
    <title>Dkwds Content: Default</title>
    <link rel="stylesheet" href="../../dist/css/dkwds-virkdk.min.css">
  </head>
  <body>
    
  <div class="usa-grid" style="padding: 2em">
    <div class="usa-width-one-whole">
      
    </div>
  </div>

    <script src="../../dist/js/dkwds.min.js"></script>
    <script>
    window.addEventListener('load', function() {
      document.body.addEventListener('submit', function(e) {
        // https://github.com/18F/web-design-standards/issues/2101
        e.preventDefault();
      }, true);
    }, false);
    </script>
  </body>
</html>
