# gifpet

https://www.npmjs.com/package/gifpet

Given a square avatar, generate a petting gif (known as "petpet" or "pet the").

The avatar will bounce up and down to simulate the petting.

Inspired by benisland (https://benisland.neocities.org/petpet/).

Further meme info: https://knowyourmeme.com/memes/pet-the-x-petthe-emotes

## Demo

![Input](/example/input.png) → ![Output](/example/output.gif)

## Usage

`npm i -S gifpet`


```
const Instance = require('gifpet');
const { Canvas } = new Instance();

let params = {
    resolution: 128, // The width (or height) of the generated gif
    delay: 20, // Delay between each frame in milliseconds. Defaults to 20.
    backgroundColor: "red", // Other values could be the string "rgba(123, 233, 0, 0.5)". Defaults to null - i.e. transparent.
}

💡 You can simply not add any parameters and leave all this empty, it's just in case you want to modify or add more things.

let animated = await Canvas.create(image, params) // You can do it without parameters too: await Canvas.create(image)

return console.log(animated)

```
Enjoying life :)
