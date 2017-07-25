dcr-s3_website
==============

Uses Docker Compose to run s3_website.

This saves us having to install s3_website locally.

For an explanation of the thinking behind this module see the blog post [Disposable Laptops With Docker Compose And NPM](http://bit.ly/2tBCYHB).

The Docker image used is [shadyoak/s3_website](https://hub.docker.com/r/shadyoak/s3_website/).

To install, do:

```shell
npm install -g dcr-s3_website
```

Once everything is set up as described on the [s3_website page](https://github.com/laurilehmijoki/s3_website), run with commands like:

```shell
$ dcr-s3_website cfg create
```
