---
title: "Hey, We are Anton Romanova and Ismael Secundar!"
meta_title: "About"
description: "this is meta description"
draft: false
image: "images/about/about.jpg"
---

<style>
  .column-container {
    display: flex;
    flex-wrap: wrap;
  }
  .column {
    flex: 1;
    padding: 10px;
  }
  .column img {
    width: 300px; /* Set a fixed width */
    height: 300px; /* Set a fixed height */
    object-fit: cover; /* Ensure the image covers the specified dimensions */
  }
</style>

<div class="column-container">
  <div class="column">
    <h2>Anton Romanova</h2>
    {{< image src="images/anton.png" caption="" alt="alter-text" height="300px" width="300px" position="center" command="fill" option="q100" class="img-fluid" title="image title"  webp="false" zoom="true" >}}
    <p>Backend developer at Duckrabbit and freelancer</p>
  </div>
  <div class="column">
    <h2>Ismael Secundar</h2>
    {{< image src="images/ismael.png" caption="" alt="alter-text" height="300px" width="300px" position="center" command="fill" option="q100" class="img-fluid" title="image title"  webp="false" >}}
    <p>Consultant at European Bank of Investment</p>
  </div>
</div>
