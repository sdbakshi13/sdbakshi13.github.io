---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<head>
  <title>Expandable Dropdown Menu Example</title>
  <script>
    function toggleDropdown() {
      var dropdownContent = document.getElementById("dropdown-content");
      dropdownContent.classList.toggle("show");
    }
  </script>
  <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML"></script>
  <script>
    function toggleOptions() {
      var options = document.getElementById("options");
      options.style.display = options.style.display === "none" ? "block" : "none";
    }
  </script>  
  <style>
    .dropdown {
      position: relative;
      display: inline-block;
    }
    
    .dropdown-content {
      display: none;
      position: absolute;
      background-color: #f9f9f9;
      min-width: 160px;
      box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
      padding: 12px 16px;
    }
    
    .dropdown:hover .dropdown-content {
      display: block;
    }
    
    .options {
      display: none;
    }
  </style>
</head>
<body>
  <nav>
    <ul class="menu">
    <li> SMEFT   Operator </li>
      <li class="dropdown">
        <button onclick="toggleDropdown()">\(X^3\)</button>
        <ul class="dropdown-content" id="dropdown-content">
          <li><a href="#">Option 1</a></li>
          <li><a href="#">Option 2</a></li>
        </ul>
      </li>
      <li class="dropdown">
        <button onclick="toggleDropdown()">\(H^6\)</button>
        <ul class="dropdown-content" id="dropdown-content">
          <li><a href="#">Option 1</a></li>
          <li><a href="#">Option 2</a></li>
        </ul>
      </li>      
      <li class="dropdown">
        <button onclick="toggleDropdown()">\(H^4 D^2\)</button>
        <ul class="dropdown-content" id="dropdown-content">
          <li><a href="#">Option 1</a></li>
          <li><a href="#">Option 2</a></li>
        </ul>
      </li>
      <li class="dropdown">
        <button onclick="toggleDropdown()">\(\psi^2 H^3\)</button>
        <ul class="dropdown-content" id="dropdown-content">
          <li><a href="#">Option 1</a></li>
          <li><a href="#">Option 2</a></li>
        </ul>
      </li><br>           
            <li class="dropdown">
        <button onclick="toggleDropdown()">\(X^2 H^2\)</button>
        <ul class="dropdown-content" id="dropdown-content">
          <li><a href="#">Option 1</a></li>
          <li><a href="#">Option 2</a></li>
        </ul>
      </li>
      <li class="dropdown">
        <button onclick="toggleDropdown()">\(\psi^2 X H \)</button>
        <ul class="dropdown-content" id="dropdown-content">
          <li><a href="#">Option 1</a></li>
          <li><a href="#">Option 2</a></li>
        </ul>
      </li>      
      <li class="dropdown">
        <button onclick="toggleDropdown()">\(\psi^2 H^2 D \)</button>
        <ul class="dropdown-content" id="dropdown-content">
          <li><a href="#">Option 1</a></li>
          <li><a href="#">Option 2</a></li>
        </ul>
      </li>
      <li class="dropdown">
        <button onclick="toggleDropdown()">\(\psi^4\)</button>
        <ul class="dropdown-content" id="dropdown-content">
          <li><a href="#">Option 1</a></li>
          <li><a href="#">Option 2</a></li>
        </ul>
      </li>            
    </ul>
  </nav>
    <h1>Click Button Options Example</h1>
  <button onclick="toggleOptions()">Click Me</button>
  <div id="options" class="options">
    <ul>
      <li>Option 1</li>
      <li>Option 2</li>
      <li>Option 3</li>
    </ul>
  </div>
  
<iframe src="https://www.wolframcloud.com/obj/47a46052-d5b0-4d65-889c-07fa98475c44?_embed=iframe" width="600" height="800"></iframe>

  <!-- Rest of your HTML content goes here -->

    
  


  


   
</body>
