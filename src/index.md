---
layout: default
title: Twenty Ninety
seo:
  image: /assets/images/meta/twenty-ninety--meta--home.png
  description: A component-based Eleventy starter kit.
---

<div class="bg-blue mb-12">
  <div class="container text-center text-white py-24">
    <h1>Hi everybody!</h1>
    <p class="text-lg mb-8">
      I'm a front-end engineer leaning towards full-stack, and I'm looking for a new challenge.
    </p>
    {% component "button",
      url = "https://drive.google.com/file/d/1k_ebSrbH-WGfbjm6RyhMzSkWabr3iNYU/view?usp=sharing",
      label = "Download my CV",
      theme = "white" %}
  </div>
</div>

<div class="container max-w-2xl">
  {% markdown %}

## Code samples to check out

![https://i.imgur.com/I0rIUcX.png](https://i.imgur.com/I0rIUcX.png)

Here's [a demo app](https://github.com/colossal-squid/vue-example-stonks-app) about monitoring stocks I did in **Vue** recently. 

There's some state-management, some web-socket code, responsive layout that doesnt break on mobile and even some unit-tests sprinkled in.

You can check it [live on GH pages too](https://colossal-squid.github.io/vue-example-stonks-app/)

## Commercial products I have worked on recently

Click around if you're curious. Of course it was a collaboration of an entire team, but my name is still somewhere on git blame in certain places, I'm sure ;) 

- [Mercedes-Benz online store](https://www.mercedes-benz.de/passengercars/buy/new-car.html)
- [Mercedes-Benz car configurator](https://www.mercedes-benz.de/passengercars/configurator.html?group=all&subgroup=see-all&view=BODYTYPE)
- [VMWare vsphere client "storage domain" wizards](https://www.youtube.com/watch?v=30YrY3gqm_k&ab_channel=DellEMC) (this is a video-tutorial about using stuff I had my hands on)

## Piano Rocker

![https://cdn.akamai.steamstatic.com/steam/apps/1771240/ss_d3f9aaaacc7a00fa5eda6f3fc54549b1fa99b499.600x338.jpg?t=1660298764](https://cdn.akamai.steamstatic.com/steam/apps/1771240/ss_d3f9aaaacc7a00fa5eda6f3fc54549b1fa99b499.600x338.jpg?t=1660298764)
I've developed a browser game about playing piano called [Piano Rocker](https://store.steampowered.com/app/1771240/) as my little free-time side project. If you're curious, here's a link to [playable demo](https://piano-rocker.roman-guivan.online/) (a MIDI keyboard is recommended but not required).

## Fun codepen stuff

Here's a snake game i did for fun: [https://codepen.io/guivarom/pen/OJzBXjK](https://codepen.io/guivarom/pen/OJzBXjK) and a slot-machine [https://codepen.io/guivarom/pen/KKQvOzE](https://codepen.io/guivarom/pen/KKQvOzE) and my cute little blog thing [https://roman-guivan.online/](https://roman-guivan.online/)
{% endmarkdown %}

  </div>
