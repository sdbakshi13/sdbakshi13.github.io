---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<head>
  <title>Dropdown Menu Example</title>
</head>
<body>
  <nav>
    <ul class="menu">
      <li><a href="{{ site.baseurl }}">Home</a></li>
      <li class="dropdown">
        <a href="#" class="dropbtn">Dropdown</a>
        <ul class="dropdown-content">
          <li><a href="#">Option 1</a></li>
          <li><a href="#">Option 2</a></li>
          <li><a href="#">Option 3</a></li>
        </ul>
      </li>
      <li><a href="{{ site.baseurl }}/about">About</a></li>
    </ul>
  </nav>
