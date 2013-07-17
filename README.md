linuxfr-solarized
=================


_linuxfr-solarized_ is a stylesheet for the essential reference of technological watch in French, [LinuxFR.org](http://www.linuxfr.org)!

The stylesheet is based on :

* [Solarized](http://ethanschoonover.com/solarized) colors
* [Knacss](http://www.knacss.com/) for the default stylesheet
* [sass](http://sass-lang.com) for the stylesheet preprocessor

Four versions of the stylesheet exists :

* light background and light code : <http://ybr.phpnet.org/linuxfr/light_light_code.css>
* light background and dark code : <http://ybr.phpnet.org/linuxfr/light_dark_code.css>
* dark background and dark code : <http://ybr.phpnet.org/linuxfr/dark_dark_code.css>
* dark background and light code : <http://ybr.phpnet.org/linuxfr/dark_light_code.css>


Screenshots
-----------

[Screenshots](https://github.com/eunomie/linuxfr-solarized/wiki/Screenshots) of versions 1 and 2.1


Development details
-------------------

I use [gitflow](https://github.com/nvie/gitflow/) to manage my repository. So `master` branch will only contains tags. If you want some more bleeding edge work, use the `develop` branch on which I push frequently my modifications. But generated will not always containing up-to-date compiled versions. You need to compiled them :

```sh
cd src
sass -t compressed light_light_code.scss:../generated/light_light_code.css
```
