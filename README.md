# CSS-Flexbox-Layout

This is a CSS microframework that uses flexbox to achieve different Layouts. It is fully responsive on different devices.
See a demo on <a href="https://codepen.io/Njoroge254/pen/dLgeWM">codepen</a>

# How it works

The microframework is simple to use and focuses on the following guidelines:
<ul>
<li>container-fluid</li>
<li>container</li>
<li>row</li>
<li>col</li>
<li>col-12</li>
<li>col-6</li>
<li>col-8</li>
<li>col-4</li>
</ul>

# Breaking it down

**container-fluid** : This is a full width (100%) wrapper

Example :
```
<div class="container-fluid"></div>
```
**container** : This is a wrapper an 80% width

Example :
```
<div class="container"></div>
```
**row** : This is an 100% row with a *display flex* style

Example :
```
<div class="row"></div>
```

**col** : This is a column with a *flex value of 1* style

Example :
```
<div class="col"></div>
```
**col-12** : This is a column with a *flex-basis value of 100%* style

Example :
```
<div class="col-12"></div>
```

**col-8** : This is a column with a *flex-basis value of 70%* style

Example :
```
<div class="col-8"></div>
```

**col-6** : This is a column with a *flex-basis value of 50%* style

Example :
```
<div class="col-6"></div>
```
**col-4** : This is a column with a *flex-basis value of 30%* style

Example :
```
<div class="col4"></div>
```

# Usage

-The highest level is the **_container_** / **_container-fluid_**<br>
-The second level is the **_row_**<br>
-The third level is the **_col-x_**<br>

This gives the structure below :
```
<body>
        <br>
        <div class="container" style="border: 1px solid #FDB99B;padding: 0.5em;">
            <div class="row" style="border: 1px solid #FDB99B;padding: 0.5em;">
                <div class="col-12" style="border: 1px solid #FDB99B;padding: 0.5em; background-color: #A770EF;">
                    <h2>Habari</h2>
                </div>
                <div class="col-12" style="border: 1px solid #FDB99B;padding: 0.5em; background-color: #A770EF;">
                    <h2>Habari</h2>
                </div>
            </div>
        </div>
        <br>
        <div class="container" style="border: 1px solid #000;padding: 0.5em;">
            <div class="row" style="border: 1px solid #000;padding: 0.5em;">
                <div class="col-6" style="border: 1px solid #000;padding: 0.5em; background-color: #00c3ff;">
                    <h2>Habari</h2>
                </div>
                <div class="col-6" style="border: 1px solid #000;padding: 0.5em; background-color: #00c3ff;">
                    <h2>Habari</h2>
                </div>
            </div>
        </div>
        <br>
        <div class="container" style="border: 1px solid #3a6186;padding: 0.5em;">
            <div class="row" style="border: 1px solid #3a6186;padding: 0.5em;">
                <div class="col-8" style="border: 1px solid #3a6186;padding: 0.5em; background-color: #89253e;">
                    <h2>Habari</h2>
                </div>
                <div class="col-4" style="border: 1px solid #3a6186;padding: 0.5em; background-color: #89253e;">
                    <h2>Habari</h2>
                </div>
            </div>
        </div>
        <br>
        <div class="container" style="border: 1px solid #000;padding: 0.5em;">
            <div class="row" style="border: 1px solid #000;padding: 0.5em;">
                <div class="col-4" style="border: 1px solid #000;padding: 0.5em; background-color: #333399;">
                    <h2>Habari</h2>
                </div>
                <div class="col-8" style="border: 1px solid #000;padding: 0.5em; background-color: #333399;">
                    <h2>Habari</h2>
                </div>
            </div>
        </div>
    </body>
```
