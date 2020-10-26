# Leto CSS framework


The minimalistic CSS Framework, which is **easy to use** and **minimizes work to a minimum**.

## Get Started

1. Get Leto from [Github](https://github.com/spootechnologies/leto/blob/master/css/leto.css)

3. Insert Leto as link tag in your html file.

```html
<link rel="stylesheet" href="[Path to Leto]/leto.css">
```

## Basic leto structure

```html
<html>
	<head>
	</head>
	<body>
		<div class="leto-frame">
			<div class="leto-container">
				<!-- main content -->
			</div>
		</div>
	</body>
</html>
```

## How to

### Create an fixed sidebar

```html
<div class="leto-frame">
	<div class="leto-group">
		<div class="leto-edge-left">
			<!-- sidebar content -->
		</div>
		<div class="leto-container">
			<!-- main content -->
		</div>
	</div>
</div>
```

### Create a responsive layout

```html
<div class="leto-group">
	<div class="leto-half-tablet leto-third-pc leto-quater-ultrawide">
		<!-- content -->
	</div>
	<div class="leto-half-tablet leto-third-pc leto-quater-ultrawide">
		<!-- content -->
	</div>
	<div class="leto-half-tablet leto-third-pc leto-quater-ultrawide">
		<!-- content -->
	</div>
	<div class="leto-half-tablet leto-third-pc leto-quater-ultrawide">
		<!-- content -->
	</div>
</div>
```

### Style a leto element

```html
<div class="leto-bubble leto-bg-mint leto-text-bold leto-border-none">X</div>
```

# Classes

## Elements

### leto-bubble
For icons or small buttons.

```html
<div class="leto-bubble">
	<!-- content -->
</div>
```

### leto-bubble-wrapper
Adds a label to leto-bubble.


```html
<div class="leto-bubble-wrapper">
	<div class="leto-bubble">
		<!-- leto-bubble content -->
	</div>
	<label></label>
</div>
```

### leto-card
Tp visualize data as card.

```html
<div class="leto-card">
	<!-- content -->
</div>
```

### leto-card-wrapper
Adds a label to leto-card.

```html
<div class="leto-card-wrapper">
	<div class="leto-card">
		<!-- leto-bubble content -->
	</div>
	<label></label>
</div>
```

### leto-button

```html
<div class="leto-button">
	<!-- content -->
</div>
```

### leto-badge
For small infos like status, last activity, etc...

```html
<div class="leto-badge">
	<!-- content -->
</div>
```

### leto-input
For any input type, textarea or select.

Text

```html
<input class="leto-input" type="text">
```

### leto-table

```html
<table class="leto-table">
	<!-- content -->
</table>
```

### leto-pile
Grouping element.

```html
<div class="leto-pile">
	<!-- content -->
</div>
```

### leto-form
Modal like class for menus or any other data who needs to be in the foreground.

```html
<div class="leto-form">
	<!-- content -->
</div>
```

### leto-backdrop
Full screen backdrop for leto-form or any other modal class

Text

```html
<div class="leto-backdrop">
	<!-- content -->
</div>
```

### leto-toast
Message class for success or error messages

```html
<div class="leto-toast">
	<!-- content -->
</div>
```

<!-- Layout Classes -->

## Layout

### leto-frame
Main Leto class. Mandatory for any Leto project.

```html
<div class="leto-frame">
	<!-- content -->
</div>
```

### leto-container
For the main content on a page.

```html
<div class="leto-container">
	<!-- content -->
</div>
```

### leto-edge
Side menu for for buttons like leto-bubble.

```html
<div class="leto-edge">
	<!-- content -->
</div>
```

### leto-subedge
Additional class for leto-edge for more detailed infos.

```html
<div class="leto-subedge">
	<!-- content -->
</div>
```

### Flexbox


#### leto-group
For a flex container (CSS Flexbox).

```html
<div class="leto-group">
	<!-- content -->
</div>
```

#### leto-row
Sets leto-group row.

```html
<div class="leto-group leto-row">
	<!-- content -->
</div>
```

#### leto-column
Sets leto-group as column.

```html
<div class="leto-group leto-column">
	<!-- content -->
</div>
```

#### leto-wrap
For wrapping the content of leto-group.

```html
<div class="leto-group leto-wrap">
	<!-- content -->
</div>
```

#### leto-horizontal
Aligns leto-group content on the horizontal axis.

```html
<div class="leto-horizontal-center">
	<!-- content -->
</div>
```

#### leto-vertical
Aligns leto-group content on the vertical axis.

```html
<div class="leto-vertical-center">
	<!-- content -->
</div>
```

#### leto-left, leto-center, leto-right
Insize a leto-group you can use these classes to align a part of the content different.

```html
<div class="leto-group">
	<div>
		<!-- content -->
	</div>
	<div class="leto-right">
		<!-- content -->
	</div>
</div>
```

### Layout classes
Layout wrapper classes to seperat content.


#### leto-full
#### leto-two-thirds
#### leto-half
...
#### leto-eight

```html
<div class="leto-full">
	<!-- content -->
</div>
```

<!-- Transformer Classes -->

## Transformer

### Background

```html
<div class="leto-bg-mint"></div>
```

### Border

```html
<div class="leto-border-mint"></div>
```

### Text

```html
<div class="leto-text-mint"></div>
```

### Height

#### leto-height
#### leto-min-height
#### leto-max-height


```html
<div class="leto-height-sm"></div>
```

### Width

#### leto-width
#### leto-min-width
#### leto-max-width

```html
<div class="leto-width-sm"></div>
```

### Display

### leto-block
### leto-inline-block
### leto-inline
### leto-flex
### leto-inline-flex
### leto-none

```html
<div class="leto-bubble leto-inline"></div>
```

### Visibility

#### leto-visible
#### leto-invisible

```html
<div class="leto-bubble leto-invisible"></div>
```

### Overflow

#### leto-overflow-scroll
#### leto-overflow-hidden
#### leto-overflow-auto

```html
<div class="leto-pile leto-overflow-auto"></div>
```

### leto-no-shrink

```html
<div class="leto-no-shirk"></div>
```

### leto-margin/leto-m

```html
<div class="leto-margin-sm"></div>
```

### leto-padding/leto-p

```html
<div class="leto-padding-sm"></div>
```

### leto-index
For changing the z-index

```html
<div class="leto-index-5"></div>
```

### leto-roundness

```html
<div class="leto-roundness-full"></div>
```

### leto-disabled

```html
<div class="leto-disabled"></div>
```

### leto-click

```html
<div class="leto-click"></div>
```

### leto-no-link

```html
<div class="leto-no-link"></div>
```

<!-- Customize -->

# Customize
To customize leto please use [leto-cli](https://github.com/spootechnologies/leto-ui)

## Basic Variables (SASS)

### Media Quries
You can customize min-width for tablet, pc, pc oversize and the min-aspect-ratio for ultrawide displays.

```sass
$tablet: 600px 
$tabletAndPC: 1024px
$pc: 1440px
$ultrawide: 1921px
```

### Media Query Specials

```sass
$ultrawideRatio: "21/9"
$superUltrawideRatio: "32/9"
$touchDevice: (hover: none) and (pointer: coarse)
```

### Sizes
Basic sizes for elements, margin, padding, etc...

```sass
$xxs: 8px
$xs: 12px
$sm: 16px
$md: 24px
$lg: 32px
$xl: 48px
$xxl: 64px
```

### Size Specials

```sass
$standardSize: $md
$elementSizeMultipier: 2
$standardRoundness: 12px
```

### Colors

```sass
$colorWhite: #fdfdfd 
$colorDarkWhite: #f2f2f2

$colorGrey: #cccccc 
$colorLightGrey: #d9d9d9
$colorLighterGrey: #e6e6e6 
$colorDarkGrey: #a6a6a6
$colorDarkerGrey: #808080

$colorBlack: #333333
$colorLightBlack: #595959


$colorYellow: #f2e76d
$colorLightYellow: lighten($colorYellow, 15%)
$colorDarkYellow: darken($colorYellow, 15%)

$colorOrange: #f29655
$colorLightOrange: lighten($colorOrange, 15%)
$colorDarkOrange: darken($colorOrange, 15%)

$colorRed: #f2616d 
$colorLightRed: lighten($colorRed, 15%)
$colorDarkRed: darken($colorRed, 15%)

$colorPurple: #c079f2
$colorLightPurple: lighten($colorPurple, 15%)
$colorDarkPurple: darken($colorPurple, 15%)

$colorBlue: #6d83f2
$colorLightBlue: lighten($colorBlue, 15%)
$colorDarkBlue: darken($colorBlue, 15%)

$colorMint: #55f2cb  
$colorLightMint: lighten($colorMint, 15%)
$colorDarkMint: darken($colorMint, 15%)

$colorGreen: #79f297
$colorLightGreen: lighten($colorGreen, 15%)
$colorDarkGreen: darken($colorGreen, 15%)
```

### Colors Dark Mode

```sass
$colorWhiteDM: #e6e6e6
$colorDarkWhiteDM: #cccccc

$colorGreyDM: #808080
$colorLightGreyDM: #999999
$colorLighterGreyDM: #b3b3b3
$colorDarkGreyDM: #666666
$colorDarkerGreyDM: #4d4d4d

$colorBlackDM: #262626
$colorLightBlackDM: #333333


$colorYellowDM: #fff673
$colorLightYellowDM: lighten($colorYellow, 15%)
$colorDarkYellowDM: darken($colorYellow, 15%)

$colorOrangeDM: #ff9e59
$colorLightOrangeDM: lighten($colorOrange, 15%)
$colorDarkOrangeDM: darken($colorOrange, 15%)

$colorRedDM: #ff6673 
$colorLightRedDM: lighten($colorRed, 15%)
$colorDarkRedDM: darken($colorRed, 15%)

$colorPurpleDM: #ca7fff  
$colorLightPurpleDM: lighten($colorPurpleDM, 15%)
$colorDarkPurpleDM: darken($colorPurpleDM, 15%)

$colorBlueDM: #738aff
$colorLightBlueDM: lighten($colorBlueDM, 15%)
$colorDarkBlueDM: darken($colorBlueDM, 15%)

$colorMintDM: #59ffd6
$colorLightMintDM: lighten($colorMintDM, 15%)
$colorDarkMintDM: darken($colorMintDM, 15%)

$colorGreenDM: #7fff9f
$colorLightGreenDM: lighten($colorGreenDM, 15%)
$colorDarkGreenDM: darken($colorGreenDM, 15%)
```

### Color Specials

```sass
$lightModeColor: $colorBlack
$lightModeBgColor: $colorWhite
$darkModeColor: $colorWhite
$darkModeBgColor: $colorBlack

$lightModeColorDM: $colorBlackDM
$lightModeBgColorDM: $colorWhiteDM
$darkModeColorDM: $colorWhiteDM
$darkModeBgColorDM: $colorBlackDM

$linkColor: $colorBlue
$linkHoverColor: darken($linkColor, 15%) 
$toastColor: $colorBlack
```

### Font

```sass
$fontLink: 'url("https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i,800,800i&display=swap")'
$fontFamily: 'Open Sans', sans-serif
```

### Font Sizes

```sass
$fontSizeXXS: 10px 
$fontSizeXS: 12px 
$fontSizeSM: 14px 
$fontSizeMD: 16px 
$fontSizeLG: 20px 
$fontSizeXL: 24px 
$fontSizeXXL: 32px 

$fontWeightLight: 300
$fontWeightRegular: 400
$fontWeightMedium: 600
$fontWeightBold: 700
$fontWeightBlack: 800
```

### Basic Margin and Padding
Used for all elements and layout classes like edge, form, etc...

```sass
	$basicPadding: $xxs
	$basicMargin: $xxs
```