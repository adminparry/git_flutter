# Introduction
preset nodejs environment


``` bash
npm install gitbook -g 
```

choose your dir

```bash 
gitbook init
```

you will obtain these file
README.md SUMMARY.md  

```bash
gitbook serve
```
you are also run gitbook --help for more information


if you wanna to publish github repository , you can do this

```bash 
npm install gh-pages -g
```

dist _book dir

```bash
gitbook build
```
publish your hub

```bash
sudo gh-pages -d _book
```

