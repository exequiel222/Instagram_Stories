<p align="center">
    <img src="logo.png" width="480” max-width="90%" alt="Instagram Stories" />
</p>
                                                                           
<p align="center">
     <img src="https://img.shields.io/cocoapods/l/BadgeSwift.svg?style=flat" />
    <img src="https://img.shields.io/badge/language-Swift%205.0-orange.svg" />
    <img src="https://img.shields.io/badge/platforms-iOS-cc9c00.svg" />
</p>


## Screenshots

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/cbf93e2e9c2c4032a1cbe7aee31a2db5)](https://app.codacy.com/gh/drawRect/Instagram_Stories?utm_source=github.com&utm_medium=referral&utm_content=drawRect/Instagram_Stories&utm_campaign=Badge_Grade_Dashboard)

<img src="https://github.com/drawRect/Instagram_Stories/blob/master/InstagramStories/Sample%20Screenshots/xr-1.png" width="250" height="500"> <img src="https://github.com/drawRect/Instagram_Stories/blob/master/InstagramStories/Sample%20Screenshots/demo.gif" width="250" height="500"> <img src="https://github.com/drawRect/Instagram_Stories/blob/master/InstagramStories/Sample%20Screenshots/xr-2.png" width="250" height="500">

## Features
* Supports portrait orientation(only) in iPhone and all orientations in iPad.
* Image Support
* Video Support
* Long press pause and play
* Manual swipe between stories
* Left tap and Right tap gestures to switch between snaps and stories
* If there is no user interruption, it will automatically move to next snap or next story, once progress bar completes.
* Image caching handled using NSCache
* Video caching handled in documents directory using FileManager.

## How To Use
* Open the project(InstagramStories) folder. You can find the Source folder inside.
* Drag and drop **Source** folder into your project.
* In your project use same **IGStoryPreviewController**.
* But do not change default code what we have written inside IGStoryPreviewController. You can add code on top of that.
* Also do not change collectionView custom cell. Use the same **IGStoryPreviewCell**.
* Because all the functionalities are handled in the IGStoryPreviewCell only.
* If there is any issue or stuck somewhere on configuring Source folder on your project, please raise issues on github. We will reply back as soon as possible.

## Requirements
* iOS 10
* Xcode 8

### Swift v4.2: https://github.com/drawRect/Instagram_Stories/tree/Swift-v4.2

## We
* Hi! We are two people joined together and spent weekends and free time to make this repo as a example of how Instagram stories built in our assumption.
* Ranjith(https://github.com/ranmyfriend), Boominadha Prakash(https://github.com/boominadhaprakash)

## Contributing
* If you like this repository please do :star: to make this useful for others.
* Feel free to contribute by [open a Issue](https://github.com/drawRect/Instagram_Stories/issues/new/choose) or [create a Pull Request](https://github.com/drawRect/Instagram_Stories/pull/new)

## License

All the code here is under MIT license. Which means you could do virtually anything with the code.
I will appreciate it very much if you keep an attribution where appropriate.

    The MIT License (MIT)
    
    Copyright (c) 2013 ranjit (ranjithkumar2010a@live.com)
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.
