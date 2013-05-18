Sass Framework
======
Currently under extreme beta.

Notes:
<ul>
<li>Seperate UI elements and prefix, eg;
  .ui-row
    .ui-block4
      .module-title
    .ui-block8
      .module-title
</li>
</ul>

<ul>
<li><del>seperating the webpage will work well so you have a layer purely for UI/UX</del></li>
<li> a layer for modules, so a product item on a grid</li>
<li>write the templates with layer UI/UX</li>
<li>site works completely then you drop your blocks in</li>
<li>the UI/UX layer are descriptive of how they look/do, .tabs, .panes</li>
<li>the modules layer is semantic to the content</li>
</ul>

Thoughts
- "its like a house to most people a house is just filled with 'rooms', to a rofessional architect he'll have an atrium, an entertaining room, a family room, a dining room... and whatever other jargon he'll use the fact that developers dont have a consistent naming convention for sites means that the point of semantic markup early loses its meaning it might be optimised and semantic for you but the next dev who comes along onto the project might've been calling his #header #top-bar"
- "to use a language that is easily accessable by all. less vauge. such as .tab , .pane or .products.grid"
