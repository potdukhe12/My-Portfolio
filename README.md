# My-Portfolio

<button onclick="window.open('https://htmlpreview.github.io/?https://raw.githubusercontent.com/potdukhe12/My-Portfolio/main/Saurabh%20Potdukhe.html', '_blank')">
  Preview
</button>

<button onclick="copyLink()">
  Copy Link
</button>


<script>
function copyLink() {
  var link = document.getElementById("copy-link").href;
  navigator.clipboard.writeText(link)
    .then(function() {
      console.log("Link copied to clipboard");
    })
    .catch(function(error) {
      console.error("Error copying link to clipboard: ", error);
    });
}
</script>
