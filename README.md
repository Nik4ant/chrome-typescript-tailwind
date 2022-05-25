# Get started
Depending on your needs choose one of this:
### Without JS framework/library
Clone [main](https://github.com/Nik4ant/chrome-typescript-tailwind) 
branch: 
```shell
git clone -b main https://github.com/Nik4ant/chrome-typescript-tailwind.git
```
### With prebuilt Solid.js 
You can read about this technology on [official website](https://www.solidjs.com/) 
or watch [100 seconds video](https://youtu.be/hw3Bx5vxKl0) by Fireship.

Clone [solid-js](link)
branch: 
```shell
git clone -b solid-js https://github.com/Nik4ant/chrome-typescript-tailwind.git
```
Then install all dependencies:
```shell
$ cd chrome-typescript-tailwind
$ npm install  # or any other packet manager
```
Now ~~suffer with JS~~ enjoy

# Restructure Static folder
You can restructure this folder however you want.
For example, you might want to do this:
```
- Static
    - Assets
        - img
        ...
    ...
``` 
Over this:
```
- Static
    - Icons
    ...
```
The max you'll have to do is to change a few lines inside 
webpack config file

---
# TODO:
1. Post article about this thingy on medium and other websites?
2. Share with fellas on Discord
3. Add optimizations for prod builds (images compression? if so I need to create an assets folder)
