# css-docs-snippets

### Menu

- best UI design reference

Make responsive design with help of best css framework and media queries. as per me bootstrap is most popular and best css framework to use for responsive desgin.

### Responsive Media Queries
```
// Extra small devices (portrait phones, less than 576px)
// No media query since this is the default in Bootstrap

// Small devices (landscape phones, 576px and up)
@media (min-width: 576px) { ... }

// Medium devices (tablets, 768px and up)
@media (min-width: 768px) { ... }

// Large devices (desktops, 992px and up)
@media (min-width: 992px) { ... }

// Extra large devices (large desktops, 1200px and up)
@media (min-width: 1200px) { ... }

// For mobile device 
@media only screen and (max-width: 768px) {
  body {
    background-color: lightblue;
  }
}
```

### .card-zoom
```
.card-zoom {
	overflow: hidden!important;
	border-radius: inherit
}

.card-zoom>[class*=card-img] {
	-webkit-transition: all .3s ease;
	transition: all .3s ease;
	-webkit-transform-origin: center center;
	transform-origin: center center
}

.card:hover>.card-zoom>[class*=card-img] {
	-webkit-transform: scale(1.1);
	transform: scale(1.1)
}
```

## Best UI design reference
- bootstrap blog - https://blog.getbootstrap.com/
