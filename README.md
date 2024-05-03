<div align="center">
  <img src="logo.png" alt="project-screenshot" width="100" height="100">
  <h1 id="title">Lumina UI/UX</h1>
  
  <p id="description">Lumina is a free and easy-to-access UI plugin for ROBLOX designed to provide developers with a streamlined solution for creating user interfaces within their games. Inspired by the simplicity and versatility of Bootstrap, Lumina aims to empower developers of all skill levels to enhance the user experience of their ROBLOX creations.</p>
  
  <div class="slideshow-container">
    <div class="mySlides fade">
      <img src="https://cdn.discordapp.com/attachments/799660302626586625/1235607851121119285/Zrzut_ekranu_2676.png?ex=6634fcfc&amp;is=6633ab7c&amp;hm=537e2b617ad6402df135ec6c0bd76f53ceaf7950912c2d335222be10add0ac4e&amp;" style="width:100%">
    </div>
    
    <div class="mySlides fade">
      <img src="https://cdn.discordapp.com/attachments/799660302626586625/1235608181128826890/Zrzut_ekranu_2677.png?ex=6634fd4a&amp;is=6633abca&amp;hm=1af98788a0e6f7c671ee676d96185000445dcb67538ba05400ed3a7cc375def3&amp;" style="width:100%">
    </div>
    
    <div class="mySlides fade">
      <img src="https://cdn.discordapp.com/attachments/799660302626586625/1235608181410107393/Zrzut_ekranu_2678.png?ex=6634fd4a&amp;is=6633abca&amp;hm=c83957486208e18fc5788bae43d8e2bd1644fa0e5585bcd29053dc4c5cbf7060&amp;" style="width:100%">
    </div>
    
    <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
    <a class="next" onclick="plusSlides(1)">&#10095;</a>
  </div>
  
  <h2>🧐 Features</h2>
  
  Here are some of the project's best features:
  
  * Easy to use ROBLOX plugin
  * Many different styles
  * Easy to customize
  * 1-click import to your game
  
  <h2>🛠️ Installation Steps</h2>
  
  <p>1. Coming soon</p>
</div>

<script>
  var slideIndex = 1;
  showSlides(slideIndex);
  
  function plusSlides(n) {
    showSlides(slideIndex += n);
  }
  
  function showSlides(n) {
    var i;
    var slides = document.getElementsByClassName("mySlides");
    if (n > slides.length) {slideIndex = 1}    
    if (n < 1) {slideIndex = slides.length}
    for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
    }
    slides[slideIndex-1].style.display = "block";  
  }
</script>

<style>
  .mySlides {
    display: none;
  }
  
  .prev, .next {
    cursor: pointer;
    position: absolute;
    top: 50%;
    width: auto;
    margin-top: -22px;
    padding: 16px;
    color: white;
    font-weight: bold;
    font-size: 18px;
    transition: 0.6s ease;
    border-radius: 0 3px 3px 0;
    user-select: none;
  }
  
  .next {
    right: 0;
    border-radius: 3px 0 0 3px;
  }
  
  .prev:hover, .next:hover {
    background-color: rgba(0, 0, 0, 0.8);
  }
</style>
