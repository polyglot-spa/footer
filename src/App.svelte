<script>
    let bananaSrc = "https://polyglot-spa.github.io/footer/assets/images/bananas.png"
    //let bananaSrc = "http://localhost:5006/assets/images/bananas.png"
</script>

<style>
  #banana-png {
      width: 200px;
  }
  #footer-text {
      font-family: Bananas-Personal;
      font-size: 50px;
  }
  #footer-link {
      margin-top: 10px;
  }
</style>

<div class="container-fluid pt-3">
    <div>
        <span id="footer-text" class="me-3">Do you like this font? Check out this artist!</span>
        <a id="footer-link"  href="https://billyargel.com/" target="_blank" rel="noopener noreferrer">
            <img id="banana-png" src={ bananaSrc } alt=""/>
        </a>
    </div>
    <div class="mt-3">
        <p class="float-end"><a href="#">Back to top</a></p>
        <p>
            Made by Eric Carter &middot; <a href="#">Privacy</a> &middot;
            <a href="#">Terms</a>
        </p>
    </div>
</div>