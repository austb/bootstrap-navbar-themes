[bootstrap-navbar-themes] (https://github.com/austb/bootstrap-navbar-themes)
=======================

## Dependencies

All dependencies required are included in the files.  
Bootstrap-Navbar-Themes requires two bootstrap.css files:
```html
<link href="css/bootstrap.min.css" rel="stylesheet" media="screen">
<link href="css/bootstrap-responsive.min.css" rel="stylesheet" media="screen">
```
It also requires jQuery and the bootstrap.js file:
```html
<script src="js/jquery-1.10.2.min.js"></script>
<script src="js/bootstrap.min.js"></script>
```

## Implementation

Only one css file is required for implementation of new themes:
```html
<link href="css/bootstrap-navbar-themes.css" rel="stylesheet" media="screen">
```
You must also set up a navbar as per <a href="http://getbootstrap.com/2.3.2/index.html" target="_blank">Bootstrap's</a> design.
An example, with as many bootstrap elements I could fit, is shown in the index.html file:
```html
<div id="themeSelector" class="navbar navbar-red navbar-fixed-top">
    <div class="navbar-inner">
        <div class="container">
            <button type="button" class="btn btn-navbar" data-toggle="collapse" data-target=".nav-collapse">
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
            </button>
            <a class="brand" href="#">Project name</a>
            <div class="nav-collapse collapse">
                <ul class="nav">
                    <li class="active"><a href="#">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <form class="navbar-form pull-left">
                        <input type="text" placeholder="Email Address" class="span2">
                        <button type="submit" class="btn">Sign Up</button>
                    </form>
                    <form class="navbar-search pull-left">
                        <input type="text" class="search-query" placeholder="Search">
                    </form>
                </ul>
                <ul class="nav pull-right">
                    <li class="dropdown">
                        <a href="#" class="dropdown-toggle" data-toggle="dropdown">
                            Themes
                            <b class="caret"></b>
                        </a>
                        <ul id="themeMenu" class="dropdown-menu">
                            <li><a>Black</a></li>
                        </ul>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</div>
```

## License

   Copyright 2013 Austin Blatt  

   Licensed under the Apache License, Version 2.0 (the "License");  
   you may not use this file except in compliance with the License.  
   You may obtain a copy of the License at  
     http://www.apache.org/licenses/LICENSE-2.0  
   Unless required by applicable law or agreed to in writing, software  
   distributed under the License is distributed on an "AS IS" BASIS,  
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  
   See the License for the specific language governing permissions and  
   limitations under the License.