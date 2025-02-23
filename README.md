
<div id="info.html"></div>

<script>
  fetch('D:\00001 - ADS DEZEMBRO 24\GitHub\UmMochileiro\Info.html')
    .then(response => response.text())
    .then(data => {
      document.getElementById('info.html').innerHTML = data;
    });
</script>
