# bootstrap-menu-hover
A simple BootStrap 3 stylesheet to allow `.dropdown-toggle` to activate on mouse hover

##Usage
```html
<div class="menu-hover">
  <div class="dropdown dropdown-toggle">
    <button class="btn btn-default">
      Dropdown
      <span class="caret"></span>
    </button>
    <ul class="dropdown-menu" role="menu">
      <li role="presentation"><a href="#" role="menuitem">Action</a></li>
      <li role="presentation"><a href="#" role="menuitem">Another action</a></li>
      <li role="presentation"><a href="#" role="menuitem">Something else here</a></li>
      <li role="presentation"><a href="#" role="menuitem">Separated link</a></li>
      <li class="dropdown dropdown-toggle" role="presentation">
        <a href="#" role="menuitem">
          Dropdown 2
          <span class="caret"></span>
        </a>
        <ul class="dropdown-menu" role="menu">
          <li role="presentation"><a href="#" role="menuitem">Action</a></li>
          <li role="presentation"><a href="#" role="menuitem">Another action</a></li>
          <li role="presentation"><a href="#" role="menuitem">Something else here</a></li>
          <li role="presentation"><a href="#" role="menuitem">Separated link</a></li>
        </ul>
      </li>
    </ul>
  </div>
</div>
```
