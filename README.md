# minesweeper-gs

[Converted basic minesweeper](https://github.com/fej-snikduj/minesweeper-nodejs/tree/master) in GreyScript. Example project for greybel.

# How to install

You require either [greybel-js](https://github.com/ayecue/greybel-js) or [greybel-vs](https://github.com/ayecue/greybel-vs).

## Via greybel-js

- Execute following command `greybel ./src/index.src . -i --env-files .env`
- Copy paste the content of `./build/installer0.src` into GreyHack CodeEditor.exe
- Execute build in CodeEditor.exe, this should install all files
- Open the index.src file via the CodeEditor.exe and build it

## Via greybel-vs

- Open `./src/index.src` in VS and press execute a build via the context menu
- Copy paste the content of `./build/installer0.src` into GreyHack CodeEditor.exe
- Execute build in CodeEditor.exe, this should install all files
- Open the index.src file via the CodeEditor.exe and build it

# How to test

```bash
greybel-execute ./src/index.src --env-files .env
```