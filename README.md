
All credit to Los Gordos at [BlokkFont](http://www.blokkfont.com/)


This Repo exists because the certificate at the official site has expired, and https links no longer get served securely. This makes it impossible to use the font in [CodePen](https://www.codepen.io), as they have recently switched from HTTP/HTTPS to HTTPS.

![blokkfont](https://cdn.dribbble.com/users/399116/screenshots/1305003/mockup_1x.png)

## Usage

#### Include it in your project

you can use either `blokkfont.css` for the rawgit links or use `blokkfont_original.css` for including the font straight from [BlokkFont](http://www.blokkfont.com/), the base URL is the same. Be aware that `blokkfont_original.css` does not serve as HTTPS.
```
<link href="https://gitcdn.xyz/repo/octoshrimpy/blokkfont/master/blokkfont.css" rel="stylesheet" type="text/css">
```
```
<link href="https://gitcdn.xyz/repo/octoshrimpy/blokkfont/master/blokkfont_original.css" rel="stylesheet" type="text/css">
```



```
@import url("https://gitcdn.xyz/repo/octoshrimpy/blokkfont/master/blokkfont.css");
```
```
@import url("https://gitcdn.xyz/repo/octoshrimpy/blokkfont/master/blokkfont_original.css");
```


#### Use it!
```
font-family: "BLOKK";
```

You can also use the `.is-blokk` class modifier to selectively turn specific elements and their children into BLOKK text.

#### Bookmarklet!
Need to easily inject it into whatever site you're on? Use this bookmarklet! Just drag the link below onto your bookmark bar. Then click the bookmarklet to inject it into the site with css classes of `.blokked` and `.redacted`. Then add the class to whatever you need to redact. It's great for screenshots!

Github doesn't allow bookmarklet urls, so head to your favorite bookmarklet creater, like [https://mrcoles.com/bookmarklet/](https://mrcoles.com/bookmarklet/) and enter the following code:

```
let link = document.createElement('link');
link.href = 'https://gitcdn.xyz/repo/octoshrimpy/blokkfont/master/blokkfont.css'; 
link.rel = 'stylesheet';
link.type = 'text/css';
document.head.appendChild(link);

let style = document.createElement('style');
document.head.appendChild(style);
style.sheet.insertRule('.blokked, .redacted { font-family: BLOKK; color: grey; }');
```

## Download it from [BlokkFont](http://www.blokkfont.com/)

[Download](https://blokkfont-losgordos.netdna-ssl.com/v2/BLOKKNeue-Regular.zip)
or [go to official download page](http://www.blokkfont.com/) (scroll down a bit)
