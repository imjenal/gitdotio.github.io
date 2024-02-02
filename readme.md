#### The documentation is not up to date.

> To add a new redirect, you need to add it on `data/redirect.json`


<div align="center">
  <img src="https://cdn.abranhe.com/projects/gitdotio/logo.svg">
  <br>
  <br>
  <br>
  <p><i>Redirect to your websites using <b>git.io</b></i></p>
</div>

## Why?

[**Git.io**](https://git.io) is a URL shortening service that will redirect to your **Github** projects. If you try to redirect to other domain out of `Github.com` (*like your website*) you won't be able to do it.

So [this project](https://github.com/gitdotio/gitdotio.github.io) will help you redirect to any website using **git.io** super easy!

## How to do it?

- Check if [git.io/YOUR-BEAUTIFUL-LINK](https://git.io/your-beautiful-link) is avilable.

![not-found](https://cdn.abranhe.com/projects/gitdotio/screenshot.png)

-  Go to **[_redirects](_redirects)**.
-  Create an **.html** file  with the name of the link you want to make.

- Inside the file you need to copy the code below and paste it on you file, change it with you content.

``` html
---
permalink: /your-beautiful-link
destination: http://your-beautiful-site.com
---
```

### So is that all?

> No!

Now you can go to [**Git.io**](https://git.io) and copy `gitdotio.github.io/your-beautiful-link` and paste your link there and when you are done,  you will have a `git.io/random-name` that will be redirected to `your-beautiful-site.com`.

**Cons**:

The [**Git.io**](https://git.io) website will only offer random short URLs.

## So what if I want a `mycool-name`?

Well to have your custom vanity URL with **git.io** you will need to use your command line.

```console
$ curl -i https://git.io -F "url=https://gitdotio.github.io/your-beautiful-link" -F "code=mycool-name"
```

where you will need to set the `url=` parameter with the link created by **gitdotio.github.io** and `code=` with the value you'd like to set.

At this point when you type `git.io/mycool-name` that will be redirected to `your-beautiful-site.com`


## Note ⚠️

Websites won't be checked, but keep in mind to don't redirect to any abusive, racist or sexist website.

To use this service since it's owned by **Github, Inc** you will need to agree with the following:

- [x] Github's [Term and conditions](https://github.com/site/terms)
- [x] Github's [Privacy](https://github.com/site/privacy)
- [x] Github's [Security Terms](https://github.com/security)

## Who to follow?

|[![Carlos Abraham Logo](https://avatars3.githubusercontent.com/u/21347264?s=50)](https://github.com/abranhe)|
| :-: |
| [Abraham Hernandez](https://github.com/abranhe) |

## License

[The UNLICENSE](https://github.com/gitdotio/gitdotio.github.com/blob/master/license)


<div align="center">
  <img src="https://cdn.abranhe.com/projects/gitdotio/logo.svg" width="35px">
</div>
