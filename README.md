## jQuery Mobile Square-UI Theme

Theme for jQuery Mobile based on [Square-UI](http://dribbble.com/shots/948195-Square-UI-Kit-Free-Download-Now/attachments/107177/).


![jQuery-Mobile-Square-UI-Theme](http://oi50.tinypic.com/347gwuq.jpg)

## Demo

[http://ququplay.github.com/jquery-mobile-square-ui-theme](http://ququplay.github.com/jquery-mobile-square-ui-theme)

## Versions

We are going to use master branch to keep up to date with jQuery Mobile versions. Previous versions will be moved to corresponding branches.

### Current branch layout
- master - jQuery Mobile version 1.4 - currently in progress not production ready yet
- jqm-1.3.1 - jQuery Mobile version 1.3.1
- jqm-1.3.0 - jQuery Mobile version 1.3.0

## Usage

Copy `jquery.mobile.square.css`, fonts and images from `generated` folder to your project.
Include link to `jquery.mobile.square.css`

```html
 <link rel="stylesheet" type="text/css" href="jquery.mobile.square.css" />
```


## Setup

In order to add a new swatch or colors you can add a new stylus file under `src/stylus/swatches/` and run [grunt](http://gruntjs.com/) from your command line.

- brew install node
- npm install -g grunt-cli
- cd to project's folder
- npm install
- grunt watch
- start modifying css/stylus files

## Contributors

* [@tomkuk](http://github.com/tomkuk)
* [@mkuklis](http://github.com/mkuklis)

##License:

[The WTFPL License](http://en.wikipedia.org/wiki/WTFPL)