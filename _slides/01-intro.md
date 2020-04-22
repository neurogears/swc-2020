---
layout: slides
title: 1. Introduction to Bonsai
permalink: /slides/intro/
---

<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<script type="text/template">

![Bonsai](../../assets/images/bonsai-lettering.svg)

### Bonsai Club
[neurogears.org/swc-2020](https://neurogears.org/swc-2020)

![SWC](../../assets/images/swc.png)

---

### Neuroscience needs makers & hackers

On the nature of system neuroscience tools:

* Accessible
<!-- .element: class="fragment" data-fragment-index="1" -->
<!-- Accessible both in the sense that everyone can use... (so many walks of life in neuroscience) -->
<!-- ... but also in the sense that they can be understood. (using a tool with understanding is transformative) -->
* Forward-thinking
<!-- .element: class="fragment" data-fragment-index="2" -->
<!--  We want our tools to push the bar of what we can measure... (vastly underpowered tools) -->
<!--  ... but equally importantly we want them to challenge and surprise us. (surprise is the basis of discovery) -->
* Versatile
<!-- .element: class="fragment" data-fragment-index="3" -->
<!--  We need to combine tools in all sorts of ways... (crazy neuro experiments) -->
<!--  ... but also be inclusive to modifications and new demands -->

---

<!-- .element: data-transition="default fade-out" -->
![Bonsai in systems neuroscience](../../assets/images/bonsai-open.svg)

--

<!-- .element: data-transition="fade-in none" -->
![Devices compatible with Bonsai](../../assets/images/bonsai-devices.svg)

--

<!-- .element: data-transition="none" -->
![Devices compatible with Bonsai](../../assets/images/bonsai-applications.svg)

</script>
</section>

<!-- Raw HTML for embedded iframe backgrounds -->
<section data-background="#000000">
    <section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
    <script type="text/template">## Example:<br>from Shuttling to Videogame</script>
    </section>
    <section data-background-iframe="https://www.youtube.com/embed/wwU6TzUJxNU?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;loop=1&amp;playlist=wwU6TzUJxNU&amp;showinfo=0&amp;rel=0&amp;html5=1">
      <table style="height: 20%; margin-top: 65%; margin-left: -78px;">
        <tr><th>Gonçalo Lopes, Kampff Lab</th></tr>
      </table>
    </section>
    <section data-background-iframe="https://www.youtube.com/embed/0gIR2f_2rMg?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;showinfo=0&amp;rel=0&amp;html5=1">
      <table style="height: 20%; margin-top: 65%; margin-left: -78px;">
        <tr><th>Danbee Kim, Kampff Lab</th></tr>
      </table>
    </section>
    <section data-background-iframe="https://www.youtube.com/embed/qXqAXgXJPmo?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;showinfo=0&amp;rel=0&amp;html5=1">
      <table style="height: 20%; margin-top: 65%; margin-left: -78px;">
        <tr><th>Lorenza Calcaterra, Kampff Lab</th></tr>
      </table>
    </section>
</section>

<!-- Raw HTML for embedded iframe backgrounds -->
<section>
  <section data-background-iframe="https://www.youtube.com/embed/0aachcS0CUY?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;loop=1&amp;playlist=wwU6TzUJxNU&amp;showinfo=0&amp;rel=0&amp;html5=1">
    <table style="height: 20%; margin-top: 65%; margin-left: -78px; color: white;">
      <tr><th>Bonsai + DeepLabCut Live</th></tr>
    </table>
  </section>
  <section>
    <img src="../../assets/images/bonsai-dlc.svg" alt="DLC Pipeline">
  </section>
</section>

<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<script type="text/template">

#### Hardware sync all devices on acquisition
![Harp-Bonsai](../../assets/images/bonsai-harp.svg)
![Clock Synchronizer](https://lh3.googleusercontent.com/1U9qDxuuLv9lUdsMwvjXV6WSBG1GVTZ5KOOAdo3ZPJURDFi8ntFhEmXrIBqjsRz71fGbzlculssJsiET4Vs7I5EJIytHO-phjL_xvokLSA-8FjhKaw=w371)

Clock deviation: ± 44 µs

</script>
</section>

<!-- Raw HTML for embedded iframe backgrounds -->
<section>
  <section data-transition="fade-out fade-in">
    <h4>Modular data acquisition interface for neuroscience</h4>
    <img src="https://images.squarespace-cdn.com/content/v1/53039db8e4b0649958e13c7b/1574273113210-4CX9F2C8RR2CVILOW4VQ/ke17ZwdGBToddI8pDm48kGuuwVLPS_RP0tQbXFCYQD0UqsxRUqqbr1mOJYKfIPR7LoDQ9mXPOjoJoqy81S2I8N_N4V1vUb5AoIIIbLZhVYwL8IeDg6_3B-BRuF4nNrNcQkVuAT7tdErd0wQFEGFSnDI_fzWSjG-nTaKLKwXhqxN-PosbykKAe4VpyL0BddSzrVR2hKTmxZKiCvfb0xUQVA/common_interface_header.png?format=1500w" alt="ONI - Open Neuro Interface" />
    <a href="https://open-ephys.org/next-gen-acquisition-system">open-ephys.org/next-gen-acquisition-system</a>
  </section>
  <section data-transition="fade-out fade-in">
    <h4>Modular data acquisition interface for neuroscience</h4>
    <img src="https://images.squarespace-cdn.com/content/v1/53039db8e4b0649958e13c7b/1574733798710-FEMR4HF1R5I4J8BX8UEB/ke17ZwdGBToddI8pDm48kA47qaxzGU3oa60Mv3IrElh7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z4YTzHvnKhyp6Da-NYroOW3ZGjoBKy3azqku80C789l0hGaawTDWlunVGEFKwsEdnE_ZbuhWuTjDl9Hn0Vaidb23CyzgPgNZ_l0zINYXrCLdg/image%2B%25283%2529.jpg?format=1500w" alt="Starter Kit">
    <a href="https://open-ephys.org/next-gen-acquisition-system">open-ephys.org/next-gen-acquisition-system</a>
  </section>
  <section data-background-iframe="https://www.youtube.com/embed/8xC404aTSUo?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;loop=1&amp;playlist=wwU6TzUJxNU&amp;showinfo=0&amp;rel=0&amp;html5=1">
    <table style="height: 20%; margin-top: 65%; margin-left: -78px;">
      <tr><th>Next gen open ephys 3d tracking</th></tr>
    </table>
  </section>
  <section>
    <h4></h4>
    <img src="https://images.squarespace-cdn.com/content/v1/53039db8e4b0649958e13c7b/1563647325514-888R4JTXR232PAGYQT0U/ke17ZwdGBToddI8pDm48kB3IFERSih8gSc9gwbTEaQN7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z4YTzHvnKhyp6Da-NYroOW3ZGjoBKy3azqku80C789l0qwNYAhhCBGzdWC7lMoYU-ya3ojHJMwcNa85ssvbLJl-kO2cj3f-oxvdCV5LnVd2Cw/image-asset.png?format=750w" alt="ONI and Bonsai">
    <small>Simultaneous 64-channel ephys, 3D-tracking, accelerometer and gyroscope measurements, and optogenetic and electrical stimulation, all acquired and controlled through Bonsai.</small>
    <a href="https://open-ephys.org/next-gen-acquisition-system">open-ephys.org/next-gen-acquisition-system</a>
  </section>
</section>

<!-- Raw HTML for embedded iframe backgrounds -->
<section>
  <section data-transition="fade-out fade-in">
    <h4>Open-source visual environment generator</h4>
    <img src="../../assets/images/bonsai-bonvision.svg" alt="BonVision-Bonsai" />
    <img src="https://bonvision.github.io/assets/Images/Demos/DemoAR_v3.gif" width="50%" alt="Augmented Reality in BonVision" />
    <a href="https://bonvision.github.io/">bonvision.github.io</a>
  </section>
  <section data-transition="fade-out fade-in">
    <h4>Handles 2D and 3D stimuli with equal ease</h4>
    <img src="https://bonvision.github.io/assets/Images/Demos/2AFC.gif" alt="2AFC in BonVision" width="45%" />
    <img src="https://bonvision.github.io/assets/Images/DemoGIFs/MonkeyGrating.gif" alt="3D scene in BonVision" width="45%" /><br>
    <a href="https://bonvision.github.io/">bonvision.github.io</a>
  </section>
  <section>
    <h4>Map logical displays to 3D space</h4>
    <img src="https://bonvision.github.io/assets/Images/DisplayLogic/CubeMapSkybox.png" alt="BonVision cube mapping" width="45%" />
    <img src="https://bonvision.github.io/assets/Images/DisplayLogic/CubemapEnvironment.gif" alt="Cubemap environment" width="45%" />
    <a href="https://bonvision.github.io/">bonvision.github.io</a>
  </section>
</section>

<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<script type="text/template">

![Bonsai workflow editor](../../assets/images/editor.jpg)

---

<!-- .element: data-transition="default none" -->
#### A metaphor for observable sequences

<img alt="Nasa twitter account" src="../../assets/images/nasatwitter.jpg" width="400"/>

--

<!-- .element: data-transition="none" -->
#### A metaphor for observable sequences

<img alt="Webcam twitter account" src="../../assets/images/webcamtwitter.jpg" width="400"/>

---

<!-- .element: data-transition="default none" -->
![Workflow](../../assets/images/cameracapture.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/framepicker-marblecanvas.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](../../assets/images/graycam.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/graycam-marble.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](../../assets/images/framepicker-key.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/framepicker-marblecanvas.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](../../assets/images/framepicker-capture.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/filecapture.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-grayscale.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/grayscalefile.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-grayscale.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/grayscaletransform.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-sample.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/sample.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/saveimagesink.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-key.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/framepicker-marblecanvas.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/conditionkey.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: middle;" -->

---

<!-- .element: data-transition="default none" -->
##### Operator Categories

![Operator categories](../../assets/images/categories-simple.svg)
<!-- .element: style="padding: 30px; display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
##### Operator Categories

![Operator categories](../../assets/images/categories.svg)
<!-- .element: style="padding: 30px; display: inline-block; vertical-align: middle;" -->

---

###### Skip

![Skip](../../assets/images/skip.svg)

---

###### Take

![Take](../../assets/images/take.svg)

---

###### SkipUntil

![SkipUntil](../../assets/images/skipuntil.svg)

---

###### TakeUntil

![TakeUntil](../../assets/images/takeuntil.svg)

---

###### CombineLatest

![CombineLatest](../../assets/images/combinelatest.svg)

---

###### Zip

![Zip](../../assets/images/zip.svg)

---

### Questions / Brainstorm

![Bonsai](../../assets/images/bonsai-lettering.svg)
# @
![SWC](../../assets/images/swc.png)

</script>
</section>