# CSE 131 Spring 2021

Public course materials for [UCSD CSE 131](https://ucsd-cse131.github.io/sp21) 

## Install

You too, can build this webpage locally, like so:

```bash
git clone https://github.com/ucsd-cse131/sp21.git
cd sp21
make
```

The website will live in `_site/`.

## Customize 

By editing the parameters in `siteCtx` in `Site.hs`

## View

You can view it by running

```bash
make server
```

## Update

Either do

```bash
make upload
```

or, if you prefer

```bash
make 
cp -r _site/* docs/
git commit -a -m "update webpage"
git push origin master
```

## Credits

This theme is a fork of [CleanMagicMedium-Jekyll](https://github.com/SpaceG/CleanMagicMedium-Jekyll) 
originally published by Lucas Gatsas.
