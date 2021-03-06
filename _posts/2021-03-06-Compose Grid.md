---
layout: post
title: JetPack Compose GridLayout with LazyVerticalFrid
categories: [Android, Kotlin]
tags: [JetpackCompose, Android, Kotlin, AndroidStudio]
description: Jetpack Compose provides very easy api for creating GridView, and that to without need of XML and Adapters ;-)
---
### JetPack Compose makes it easier to create GridLayout easily with ```LazyVerticalGrid```.


> ```LazyVerticalGrid``` is currently a ```ExperimentalFoundationApi```



```LazyVerticalGrid``` provides ```cells``` which takes instance of ```GridCells``` which allows you to define number of cells you want to display in the Grid.
If you want fix size cell use  ```GridCells.Fixed()``` and if you want to have adaptive cells then use ```GridCells.Adaptive()```.


#### Here is a quick code for the Firend Grid in our app.
![image](/assets/images/FriendsGrid.png)
> code snippet represent amount of code it requires to make GridLayout.

#### Here is a code for Friend Grid Item
![image](/assets/images/FriendListItem.png)


##### Complete source code for the post can be found at [Github](https://github.com/pinakinkansara/ComposePlayGround/tree/gridview)