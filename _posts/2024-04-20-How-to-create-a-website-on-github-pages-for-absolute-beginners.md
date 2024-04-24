---
layout: post
title:  How to create a website on github pages (in progress)
subtitle: for absolute beginners
cover-img: /assets/img/web-dev-pic.jpg
thumbnail-img: /assets/img/hatsune-miku.png
share-img: /assets/img/hatsune-cute.jpg
tags: [webdev]
author: mach
---
I'm writing this tutorial because it might come in handy in the future, since I will probably forget everything I just learned until the next time I will need it. So I've decided to write it down. 

<h1>The easiest way </h1>

You can find someone else's github repository with their own custom Jekyll theme and then you will fork it. [https://github.com/topics/jekyll-theme](https://github.com/topics/jekyll-theme)
I used this repository [https://github.com/daattali/beautiful-jekyll](https://github.com/daattali/beautiful-jekyll) and I believe you can fork other repositories the same way as I did with this repository from daattali.

{: .box-note}
**Note:** Jekyll is a static site generator written in Ruby used to customizing design of the website.

1. Click on the fork button (button at the top right corner) to fork your chosen repository. New window will open.
2. Rename the repository, so it would include your username in its name. (In my case it was machgg.github.io --> my username is machgg)
3. Create the repository. This will create a copy of the repository in your account. Now you can search for your website with yourusername.github.io (example with my own username: machgg.github.io) and your website is online now. Letsgooooo.
4. If you want to make changes to your website, go to your repository. In the files list on the left side you'll find a file named _config.yml. So for example, you can change the title or the logo of the website.

If you are working with beautiful-jekyll from daattali and you don't want the jekyll logo on your website, delete this part of the _config.yml on 35th row of the file:

```avatar: "/assets/img/avatar-icon.png"```

If you would like to change the picture, go again to files list of your repository and open assets folder and then img folder. Then upload image that you would like to use as your logo. After that copy the name of your image (in my case: small-charming-kitten-office-near-keyboard-kitten-is-exploring-computer_199743-16006.jpg) and open file _config.yml again. Find row 35 and insert coppied name of your image behind the ```avatar: "/assets/img/``` part, so it would look like this:

```avatar: "/assets/img/small-charming-kitten-office-near-keyboard-kitten-is-exploring-computer_199743-16006.jpg"```

Wanna make your own repository from the beggining and make it more difficult for yourself? Here you go bestie. You can either start from the beginning and use the supported github themes ([https://pages.github.com/themes/](https://pages.github.com/themes/)) or start from the scratch and create your own (but that is advanced skill and you would have to do your own research and learning, cuz I don't know much about this one (yet)).

The positive thing about the more dificult way to create your own website with supported github theme:
- You don't have to fork anyone's repository, you will have your own work and you will probably learn new things

The negative thing:
- Supported github themes are not that visually pleasing as themes, that you can fork
- Be prepared that you will have to install Jekyll and Ruby.

Important resources: (will work on this part later)

[https://pages.github.com/](https://pages.github.com/)

[https://www.youtube.com/watch?v=QyFcl_Fba-k&t=262s](https://www.youtube.com/watch?v=QyFcl_Fba-k&t=262s)

How to install Jekyll
- install Ruby

How to install and run Jekyll on Windows 10 - by devn8
[https://www.youtube.com/watch?v=HlfvhkDuicc&list=WL&index=6&pp=gAQBiAQB](https://www.youtube.com/watch?v=HlfvhkDuicc&list=WL&index=6&pp=gAQBiAQB)

[https://www.youtube.com/watch?v=LfP7Y9Ja6Qc&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=3](https://www.youtube.com/watch?v=LfP7Y9Ja6Qc&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=3) 
--> 4.43
--> just checking if everything was installed:
```ruby -v```
```gem -v```
```jekyll -v```

Jekyll theme
[https://www.youtube.com/watch?v=NoRS2D-cyko&t=312s](https://www.youtube.com/watch?v=NoRS2D-cyko&t=312s) 
