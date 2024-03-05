---
marp: true
theme: minecraftonmarp
---

<!-- Scoped style -->
<style scoped>
    pre{
        margin: 0;
        padding: 0;
        width: 5940px;
        height: 4200px;
        background: none;
        border: 0;
        position: absolute;
        z-index:0;
        backdrop-filter: blur(0px)
    }

    h1 {
        position: absolute;
        top: 23%;
        left: 59%;
        transform: rotate(-15deg);
        color: yellow;
        text-shadow: 4px 4px #000A;
        animation-name: text;
        animation-duration: 0.75s;
        animation-iteration-count: infinite;
        animation-timing-function: linear;
        white-space: nowrap;
    }

    /* Animation for yellow menu text */
    @keyframes text {
        0%   {transform: rotate(-15deg) scale(1);}
        50%  {transform: rotate(-15deg) scale(1.1);}
        100% {transform: rotate(-15deg) scale(1);}
    }

    img{
        display: flex; 
        justify-content: center; 
        align-items: center;
        margin: 0 auto;
        padding: 0;
        object-fit:cover;
        border:none;
        box-shadow: none;
        image-rendering: pixelated;
    }

    img:nth-of-type(1){
        width: 70%;
        margin-bottom: -11%;
    }
    img:nth-of-type(2){
        width: 35%;
        margin-bottom: 7%;
    }

    *, ::before, ::after {
        z-index: 2;
        box-sizing: border-box;	margin: 0; padding: 0;
    }

    section {
        display: flex; 
        justify-content: center; 
        align-items: center;
        flex-direction: column;
        background-color: #fff;
        background-image: url(assets/panorama.png);
        background-size: 5940px 4200px;
        font-size: 18pt;
        border: 0;
        animation-name: pancam;
        animation-duration: 120s;
        animation-iteration-count: infinite;
        animation-timing-function: linear;
    }

    /* Animates the background movement */
    @keyframes pancam {
        0%   {background-position: -1000px -2000px;}
        25%  {background-position: -2000px -1750px;}
        50%  {background-position: -3000px -1750px;}
        100% {background-position: -4000px -2000px;}
    }

    /* The menu layout */
    ul {
        --btn-size: 43pt;
        display: grid;
        grid-template-columns: var(--btn-size) calc(var(--btn-size) * 10) var(--btn-size);
        grid-template-rows: repeat(3, var(--btn-size)) 16px var(--btn-size);
        grid-template-areas:
        '. first .'
        '. second .'
        '. third .'
        '. .  .'
        'lang fourth access'
        ;
        grid-gap: 12px;
    }

    /* Sets all the button positions... theres probably a better way of doing this */
    ul li:nth-of-type(1){ grid-area: first;}
    ul li:nth-of-type(2){ grid-area: second;}
    ul li:nth-of-type(3){ grid-area: third;}
    ul li:nth-of-type(4){ grid-area: lang;}
    ul li:nth-of-type(5){ grid-area: fourth; width: 49%}
    ul li:nth-of-type(6){ grid-area: fourth; margin-left: 52%; width: 49%}
    ul li:nth-of-type(7){ grid-area: access}

    ul li img {
        width: 100%; height: 100%;
        padding: 4pt;
        padding-bottom: 8pt;
        object-fit: contain;
    }

    ul li:nth-of-type(7) img {
        padding: 0pt;
        padding-bottom: 4pt;
    }

    ul li::before{
        background: none;
        width: 0;
    }

    /* Minecraft button */
    ul li {
        display: flex;
        width: 100%; height: 100%;
        cursor: pointer;
        overflow: hidden;
        white-space: nowrap;
        user-select: none;

        background: #999 url(assets/defaulttexturepack/gui/sprites/widget/button.png) center / cover;
        image-rendering: pixelated;
        border: 2px solid #000;
        list-style: none;
        align-items:center;
        justify-content:center;

        color: #DDD;
        text-shadow: 2px 2px #000A;
        
    }
    
    /* Mouse over */
    ul li:hover {
        background-color: rgba(100, 100, 255, .45);
        text-shadow: 2px 2px #202013CC;
        border: 3px solid white;
    }

    ul li:active {
        box-shadow: inset -2px -4px #0004, inset 2px 2px #FFF5;
    }
    
    /* Button title */
    h2{
        position: absolute;
        bottom: 0;
        color: #DDD;
        font-size: 18pt;
    }

    h2:nth-of-type(1){
        left: 5px;
        text-align: left;
    }

    h2:nth-of-type(2){
        right: 5px;
        text-align: right;
    }

    h2:nth-of-type(2):hover{
        text-decoration: underline;
        text-decoration-thickness: 4pt;
    }
</style>
<!-- An empty code block to force layou -->
```



```
<!-- Logos and subtext -->
![](assets/defaulttexturepack/gui/title/minecraft.png)
![](assets/defaulttexturepack/gui/title/edition.png)

# A marp theme!

- Made by
- Mikael
- github/mikael-ros/minecraft-on-marp
- ![](assets/images/logo1.png)
- Options
- Quit Game
- ![](assets/images/logo2.png)

## Secondary text :)

## ~~Copyright~~ not me! :o 2099

---

<!-- Scoped style -->
<style scoped>
    section {
        background-color: rgb(220,220,240);
        background-image: url(assets/images/example-background.png), linear-gradient(white, grey);
        background-blend-mode: multiply;
        border-image: url(assets/borders/slice_of_cake2.png) 16 / 16px / 0 round;
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
        background-image: url(assets/defaulttexturepack/gui/sprites/icon/unseen_notification.png);
    }

    li li::before{
        background-image: url(assets/defaulttexturepack/gui/sprites/notification/more.png);
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
        background-image: url(assets/defaulttexturepack/block/bricks.png), linear-gradient(white, grey);
        background-blend-mode: multiply;
        background-repeat: repeat;
        background-size: 64px;
        image-rendering: pixelated;
        border-image: url(assets/borders/dark_oak_log.png) 16 / 16px / 0 round;
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
        background-image: url(assets/defaulttexturepack/gui/sprites/statistics/item_crafted.png);
    }
</style>



# Split page

![bg right:40%](assets/images/example.png) 
This is an image caption :o
_This is a subcaption :O_
-->



## Another page

On this slide we have some icons for indexing. Pretty neat.

<!-- Icons for slides -->
![icon](assets/defaulttexturepack/gui/sprites/server_list/pinging_1.png)
![icon](assets/defaulttexturepack/gui/sprites/server_list/ping_1.png)

---

<!-- Scoped style -->
<style scoped>
    section {
        background-color: rgb(100,100,100);
        background-image: url(../Resurser/Images/ricketyassmcscreenshot.png), linear-gradient(white, grey);
        background-blend-mode: multiply;
        background-size: 2000px;
        background-position: -400px -40px, 0 0;
        border-image: url(../Resurser/Borders/oak_planks.png) 16 / 16px / 0 round;
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
        background-image: url(assets/defaulttexturepack/item/oak_door.png);
    }
    li:nth-of-type(2)::before{
        background-image: url(assets/defaulttexturepack/item/redstone.png);
    }
    li:nth-of-type(3)::before{
        background-image: url(assets/defaulttexturepack/item/oak_boat.png);
    }
    li:nth-of-type(4)::before{
        background-image: url(assets/defaulttexturepack/item/cake.png);
    }

    
</style>



![bg right:40%](assets/images/example.png)
Image caption

![icon](assets/defaulttexturepack/gui/sprites/server_list/pinging_1.png)
![icon](assets/defaulttexturepack/gui/sprites/server_list/ping_2.png)

# Mixed content
### Subsubheading

> Some extra context, or a nice quote!

#### Subsubsubsubheading 
- We love doors!
- Blood sacrifice
- Hunted for sport by lilypads (in the past)
- Certainly not a lie
