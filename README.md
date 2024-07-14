## GIFPET

> You can get it from NPM [@gifpet](https://www.npmjs.com/package/gifpet).

Given a square avatar, generate a petting gif **(known as "petpet" or "pet the")**.

The avatar will bounce up and down to simulate the petting.

### Inspired by benisland
> [@benisland](https://benisland.neocities.org/petpet/)

### Further meme info
> [@Info](https://knowyourmeme.com/memes/pet-the-x-petthe-emotes)

## Demo

![Input](/example/input.png) → ![Output](/example/output.gif)

## Installation & Use

> npm i -S gifpet

```Javascript
const Instance = require('gifpet');
const { Canvas } = new Instance();
```

**💡 You can simply not add any parameters and leave all this empty, it's just in case you want to modify or add more things.**

```Javascript
let params = {
    resolution: 128, // The width (or height) of the generated gif
    delay: 20, // Delay between each frame in milliseconds. Defaults to 20.
    backgroundColor: "red", // Other values could be the string "rgba(123, 233, 0, 0.5)". Defaults to null - i.e. transparent.
}
```
- let image = 'https://vangh.org/schema/image/image.png' 
> It also works by simply using a buffer, instead of a url.

**let animated = await Canvas.create(image, params)** 
> You can do it without parameters too: **await Canvas.create(image)**

**return console.log(animated)**

> Enjoying life :)
