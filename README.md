## Whole page slider

You can see a working [demo here](https://elansx.github.io/Slider/)

Swiping works on both - mobile (touch) and desktop (mouse) devices.


### Getting started

Place this stylesheet in your page header
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elansx/Slider/slider.css">
```

Now create structure for your sections and pages
```
<body id="page">

    <section>
      <div class="page">
        <h1>First section</h1>
        <p>And his single page</p>
      </div> 
    </section>


    <section>
       <div class="page">
         <h1>Second section</h1>
          <p>First page</p>
       </div>

       <div class="page">
         <h1>Still second section</h1>
         <p>But his second page...</p>
       </div>
    </section>
    
<!-- Here goes the script -->

</body>
```
Kickstart the slider - place this code at the bottom of body element

```
<script src="https://cdn.jsdelivr.net/gh/elansx/Slider/slider.js"></script>
<script>
    XYSlider("container", {
        colors: ['lightskyblue', 'orange']
    })
</script>

```
