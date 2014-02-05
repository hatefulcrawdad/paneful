#Paneful
Painless off-canvas layouts with no JS

Still working on this project. It does currently work if you use the file structure below: 

```
<!-- Left side menu -->
<input type="checkbox" class="paneful-toggle" id="panefulToggle_Left">
<ul class="paneful-left">
  <li><a href="#">Menu Item</a></li>
</ul>

<!-- Right side menu -->
<input type="checkbox" class="paneful-toggle" id="panefulToggle_Right">
<ul class="paneful-right">
  <li><a href="#">Blah</a></li>
</ul>


<div class="paneful-page-wrap">
  <!-- Paneful menu labels -->
  <label class="paneful-toggle-left" for="panefulToggle_Left">Left Menu</label>
  <label class="paneful-toggle-right" for="panefulToggle_Right">Right Menu</label>

  <!-- Page content here -->
  
</div>
```
