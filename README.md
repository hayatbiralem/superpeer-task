# Superpeer Task

This project tries to solve the task on https://kodilan.com/ilanlar/superpeer-ui-developer

## Demo

You can check the result on both desktop and mobile devices by visiting http://superpeertask.test.rebootworks.com/

## Usage

```
git clone git@github.com:hayatbiralem/superpeer-task.git
cd superpeer-task
yarn install
yarn dev
```

And then visit http://localhost:1234/

## Points I care about

- I used Parcel to package things.
- I used [InuitCSS Architecture](https://github.com/inuitcss/inuitcss) based on ITCSS and BEM Methodology. Probably you know that but this is not a CSS Framework like Bootstrap. It does not contain any cosmetics.
- I used comments to make things clear in HTML and CSS.
- I tried to use semantic syntax and accessibility attributes.
- I used inline SVG sprite.
- I tried to achieve pixel perfect by using screenshots as layers in Photoshop. See the [pixel-perfect.png](pixel-perfect.png) file.
- I used responsive images.
- I made sure that the real mobile experience can be tested at widths of 479px and below.
- I used mobile first approach.
- I checked Chrome, Firefox, Opera, Edge, IE11, iOS Safari/Chrome, Android Default/Chrome browsers.
- I fixed the select apperance issue at IE11.
- I fixed the iOS Safari input zoom problem caused by the input size being 15px (below 16px) and I made a sass mixin for it.
- I couldn't solve the text ellipsis issue on IE11 with only CSS but I could with some Javascript by following [this approach](https://nikitahl.com/text-overflow-ellipsis-on-select-tag/).
