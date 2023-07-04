# Geopard.FlexGrid Package for Neos CMS #

A simple but full featured flexbox grid Package for Neos <i>CMS</i>. It's using a 12 grid layout and unique class names.

## Why this package?
There are already numerous Neos packages for creating a grid. However, the packages we tested didn't meet all of our needs. This package can be used to create a grid with features listed below. The settings are numerous, but do not have to be made if the use case has to be simple.

## Features
Geopard.FlexGrid allows different column sizes to be specified for xs, sm, md, and lg viewports. All following features can be configurated for every available viewport in the neos backend.
- Auto Sizing
- Nesting
- Column Order
- Column Offset
- Column position (vertical & horizontal)

![Preview](.github/preview.png?raw=true "Preview")
*Note that the row padding and colors shown in this preview are for demo purposes only. It's not part of this package.

## Installation
```
composer require geopard/flexgrid
```

## Configuration

No further settings are necessary during installation. Install and get started.

#### You want to use your own css?
Disable CSS from this package by using the following configuration in your site package settings.yaml: 
```
Geopard:
  FlexGrid:
    includeCss: false
```
