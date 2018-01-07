# Parser starcraft builds

Took builds from this [site](https://lotv.spawningtool.com/build/)

## Installing
For working need [jupyter notebook](http://jupyter.org/)

installing jupyter is described [here](http://jupyter.org/install.html)

for install required libs need run first cell 
```
!pip install numpy pandas requests bs4
```
if it doesn't work, try
```
!pip3 install numpy pandas requests bs4
```

## What was parsed
### From page with build orders
- matchup
- build's type

![home](https://user-images.githubusercontent.com/24289268/34647800-0064f4da-f3b7-11e7-9c38-18bcfe65f707.png)

### From pages with each build order
- title
- time of published
- time of modified (if exist)
- actions of build order 

![build](https://user-images.githubusercontent.com/24289268/34647986-44230992-f3bb-11e7-8189-21e047290a7f.png)
