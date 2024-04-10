Generate completely new music from a text description!

#DEMO
Try it here:
https://flatsiedatsie.github.io/transformers_js_musicgen/

##About
This is a small demonstration of running Facebook's MusicGen-Small AI model through Transformers.js. This means it's fully browser based; everything runs on your own computer. This is a complete demo, with all the required files.

More about MusicGen: https://huggingface.co/facebook/musicgen-small



## Troubleshooting
Have a look at this Github thread:
https://github.com/xenova/transformers.js/issues/688

##Manual update
In the `js` folder you'll find a full distribution of an alpha version of Transformers.js 3.0. You will likely wish to generate a newer version of Transformers.js yourself. 

For example, while version 3 is in beta, you could run:

```
git clone -b v3 https://github.com/xenova/transformers.js.git
cd transformers.js/
npm i
npm run build
```
(you may need to also install a compiler that allows you to generate .wasm files)

This will generate the new version in a sub-folder called 'dist'. Rename that folder to 'js' and use it to replace the old js folder (and clear your browser cache).
