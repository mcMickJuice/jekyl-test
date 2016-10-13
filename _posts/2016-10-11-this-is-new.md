---
layout: post
title: "new post"
---

Here's a hip new page. Check it out!

<div id="element">
    Here's something!
</div>

<script>
var elem = document.getElementById('element')

setTimeout(() => {
    elem.innerHTML = 'oh hey this is changede!'
}, 2000)
</script>