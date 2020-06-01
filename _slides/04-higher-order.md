---
layout: slides
title: 4. Higher Order Operators
permalink: /slides/higher-order/
---

<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<script type="text/template">

![Bonsai](../../assets/images/bonsai-lettering.svg)

### Higher Order Operators
[neurogears.org/swc-2020](https://neurogears.org/swc-2020)

![SWC](../../assets/images/swc.png)

---

### Outline

* SelectMany
* Buffer/Window
* Applications

---

<!-- .element: data-transition="default none" -->
###### Transform

![Transform](../../assets/images/transform.svg)

--

<!-- .element: data-transition="default none" -->
###### Select

![Select](../../assets/images/select.svg)

--

<!-- .element: data-transition="none default" -->
###### SelectMany

![SelectMany](../../assets/images/selectmany.svg)

--

<!-- .element: data-transition="none default" -->
###### SelectMany: Play audio on cue

![SelectMany](../../assets/images/selectmany-playsound-1.svg)

--

<!-- .element: data-transition="none default" -->
###### SelectMany: Play audio on cue

![SelectMany](../../assets/images/selectmany-playsound-2.svg)

---

<!-- .element: data-transition="default none" -->
###### Buffer

![Buffer](../../assets/images/buffer.svg)

--

<!-- .element: data-transition="none default" -->
###### Buffer: Moving Average

![SelectMany](../../assets/images/buffer-movingaverage.svg)

---

<!-- .element: data-transition="default none" -->
###### TriggeredBuffer

![TriggeredBuffer](../../assets/images/triggeredbuffer.svg)

--

<!-- .element: data-transition="none default" -->
###### TriggeredBuffer: Signal Snapshot

![SelectMany](../../assets/images/triggeredbuffer-snapshot.svg)

---

###### Window

![Window](../../assets/images/window.svg)

---

<!-- .element: data-transition="default none" -->
###### TriggeredWindow

![TriggeredWindow](../../assets/images/triggeredwindow.svg)

--

<!-- .element: data-transition="none default" -->
###### TriggeredWindow: Record triggered video

![SelectMany](../../assets/images/triggeredwindow-recordclip.svg)

---

### Higher-Order Applications

![Concatenate video files using first order operators](../../assets/images/concatfile-firstorder.svg)

--

###### Enumerate Files

![Enumerate all file names in a folder](../../assets/images/concatfile-enumeratefiles.svg)

--

###### Create Observable

![Create sequences of frames from file names](../../assets/images/concatfile-observable.svg)

--

###### Concat

![Combine all sequences of frames into a single sequence](../../assets/images/concatfile-combine.svg)

--

###### Higher-Order: Batch concatenate multiple videos

![SelectMany](../../assets/images/higherorder-concatfiles.svg)

</script>
</section>