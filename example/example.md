---
marp: true
theme: minecraft-on-marp
---
<!-- _class: menu -->

<!-- An empty code block to force layout -->
```



```
<!-- Logos and subtext -->
![](../assets/defaulttexturepack/gui/title/minecraft.png)
![](../assets/defaulttexturepack/gui/title/edition.png)

# A marp theme!

- Made by
- Mikael
- github/mikael-ros/minecraft-on-marp
- ![](../assets/defaulttexturepack/gui/sprites/icon/language.png)
- Options
- Quit Game
- ![](../assets/defaulttexturepack/gui/sprites/icon/accessibility.png)

## Minecraft on Marp 0.0.1

## ~~Copyright~~ not me! :o 2024

---

<!-- Scoped style -->
<style scoped>
    section {
        background-color: rgb(220,220,240);
        background-image: url(../assets/images/example-background.png), linear-gradient(white, grey);
        background-blend-mode: multiply;
        border-image: url(../assets/borders/slice_of_cake2.png) 16 / 16px / 0 round;
    }

    h2{
        margin: 0 0 0.5cm 0;
        mix-blend-mode: soft-light;
    }
    
    img{
        display: inline-block;
        height: 200px;
        object-fit:cover;
        float:left;
        border:none;
    }
    

    li::before{
        background-image: url(../assets/defaulttexturepack/gui/sprites/icon/unseen_notification.png);
    }

    li li::before{
        background-image: url(../assets/defaulttexturepack/gui/sprites/notification/more.png);
    }

</style>

# Introduction

- Main point
    - Sub point!
    - Yeah :)

---

<!-- Scoped style -->
<style scoped>
    section {
        background-color: rgb(200,180,180);
        background-image: url(../assets/defaulttexturepack/block/bricks.png), linear-gradient(white, grey);
        background-blend-mode: multiply;
        background-repeat: repeat;
        background-size: 64px;
        image-rendering: pixelated;
        border-image: url(../assets/borders/dark_oak_log.png) 16 / 16px / 0 round;
    }

    img{
        position: absolute;
        image-rendering: auto;
        z-index: 1;
    }

    p:first-of-type{
        position: absolute;
        right: 26px;
        bottom: 50px;
        color: var(--color-two);
        text-align: right;
        font-size: 0.7em;
    }

    p:first-of-type em{
        opacity: 65%;
        font-size: 0.9em;
    }

    em{
        color: var(--color-two);
    }

    li::before{
        background-image: url(../assets/defaulttexturepack/gui/sprites/statistics/item_crafted.png);
    }
</style>

![bg right:50%](https://images.unsplash.com/photo-1497752531616-c3afd9760a11?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D) 
This is an image caption :o
_Photo by [Gary Bendig](https://unsplash.com/@kris_ricepees?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash) on [Unsplash](https://unsplash.com/photos/raccoon-walking-on-lawn-grass-6GMq7AGxNbE?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash)_ -->

# Split page

## Another page

On this slide we have some icons for indexing. Pretty neat.

<!-- Icons for slides -->
![icon](../assets/defaulttexturepack/gui/sprites/server_list/pinging_1.png)
![icon](../assets/defaulttexturepack/gui/sprites/server_list/ping_1.png)

---

<!-- Scoped style -->
<style scoped>
    section {
        background-color: rgb(100,100,100);
        background-image: url(../assets/images/example.png), linear-gradient(white, grey);
        background-blend-mode: multiply;
        background-size: 2000px;
        background-position: -400px -40px, 0 0;
        border-image: url(../assets/borders/oak_planks.png) 16 / 16px / 0 round;
    }

    * {
        z-index: 2;
    }

    section > p:first-of-type{
        position: absolute;
        right: 26px;
        bottom: 10px;
        font-size: 0.7em;
        color: var(--color-two);
    }

    /* Specific icons per li element */
    li:nth-of-type(1)::before{
        background-image: url(../assets/defaulttexturepack/item/oak_door.png);
    }
    li:nth-of-type(2)::before{
        background-image: url(../assets/defaulttexturepack/item/redstone.png);
    }
    li:nth-of-type(3)::before{
        background-image: url(../assets/defaulttexturepack/item/oak_boat.png);
    }
    li:nth-of-type(4)::before{
        background-image: url(../assets/defaulttexturepack/item/cake.png);
    }

    
</style>



![bg right:40%](https://images.unsplash.com/photo-1551647152-eb24b93db57b?q=80&w=2083&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)
This is another image caption :o
_Photo by [Zdeněk Macháček](https://unsplash.com/@zmachacek?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash) on [Unsplash](https://unsplash.com/photos/two-brown-and-black-mammals-clinging-on-tree-trunk-dWlf3CFPn9Y?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash)_ -->

![icon](../assets/defaulttexturepack/gui/sprites/server_list/pinging_1.png)
![icon](../assets/defaulttexturepack/gui/sprites/server_list/ping_2.png)

# Mixed content
### Subsubheading

> Some extra context, or a nice quote!

#### Subsubsubsubheading 
- We love doors!
- Blood sacrifice
- Hunted for sport by lilypads (in the past)
- Certainly not a lie
