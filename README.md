<!-- index.html -->
<div id="header"></div>

<script>
  fetch("header.html")
    .then(response => response.text())
    .then(data => {
      document.getElementById("header").innerHTML = data;
    });
</script>
