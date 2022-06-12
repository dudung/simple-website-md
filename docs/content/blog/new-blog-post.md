# new blog post
It is a new blog post, posted on 12 Jun 2022 at 1358.


## local image
Local image can be inserted using its relative path

![](../../img/swm-icon.png)

which is produced using

<pre>
![](../../img/swm-icon.png)
</pre>

since the directory structure is as follow

```
\
├── css
│   └── simple-website.css
├── img
│   └── swm-icon.png
├── js
│   └──script.js
├── content
│   ├── blog
│   │   └── new-blog-post.md
│   ├── code
│   │   └── a-code-post.md
│   └── todo
│       └── 12-jun-2022.md
├── about.md
└── index.md
```

where the image is `swm-icon.png` and this file is `new-blog-post.md`.



## remote image
Remote image can be inserted using its url

![](https://live.staticflickr.com/65535/52138328472_ed03a19955_w.jpg)

yang diperoleh dengan

<pre>
![](https://live.staticflickr.com/65535/52138328472_ed03a19955_w.jpg)
</pre>

yang merupakan salah satu ukuran dari foto [roti-opa-fuer-adik](https://www.flickr.com/photos/195637519@N06/52138328472).
