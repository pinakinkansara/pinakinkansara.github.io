---
layout: post
title: JetPack Compose GridLayout
categories: [Android, Kotlin]
tags: [JetpackCompose, Android, Kotlin, AndroidStudio]
description: Jetpack Compose provides very easy api for creating GridView, and that to without need of XML and Adapters ;-)
---
JetPack Compose makes it easier to create GridLayout easily with ```LazyVerticalGrid```.

```LazyVerticalGrid``` provides ```cells``` which takes instance of ```GridCells``` which allows you to define number of cells you want to display in the Grid.
If you want fix size cell use  ```GridCells.Fixed()``` and if you want to have adaptive cells then use ```GridCells.Adaptive()```.


we want to display list of friends in Grid view and below is the code that is required to draw the grid in Compose.
![image](/assets/images/FriendsGrid.png)