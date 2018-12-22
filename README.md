# Contributing to VectorLogoZone [<img alt="VLZ Logo" src="https://www.vectorlogo.zone/logos/vectorlogozone/vectorlogozone-tile.svg" height="96" align="right"/>](https://www.vectorlogo.zone)


## General SVG Guidelines

These guidelines apply to all images except the `-official` images.

 * No company/legal suffixes (such as Corp, GmbH, Ltd, SA, NV)
 * No legal turds (such as &copy;, &trade;)
 * No taglines
 * Transparent background
 * Dark foreground, so it looks good on a white/light background (except `-tile`).

## Naming guidelines

Each logo has a unique id (`logohandle` in the metadata) that is used in the directory and file name.

Use the base domain name without the `www.`.  If the top-level domain is `.com` or `.org`, drop that as well.
  
If the home page is a subdirectory or subdomain, put an underscore and then the subdirectory/subdomain.

Some examples:LATER

## Image types

Required:
 * **Rectangle** (`-ar21`) - a 120x60 rectangle with the logo and the name, with some padding
 * **Icon** (`-icon`) - a 64x64 with just the logo (i.e. no name) on a transparent (white) background, with no padding other than to make it square
 
Optional:
 * **Tile** (`-tile`) - a 512x512 image with a simple logo on a colored background.  
 * **Image** (`-image`) - a 64 high image: the same as the icon, but resized so that it is 64 high with no padding
 * **Horizontal** (`-horizontal`) - 
 * **Wordmark** (`-wordmark`) - 60 high, just the name, in black, with padding
 * **Official** (`-official`) - The official logo, unchanged except cropped and resized to a maximum of 256 height or width.
 
Other
 * **Card** (`-card`) - this is a 480x240 raster image that is automatically generated from the `-ar21` image during the
   website deployment.  It should not be checked into git.
   
## Basic Metadata

 * colors - array of colors used in the logo
 * font - LATER
 * guidelines - link to official logos and/or usage guidelines
 * images - list of available images.  This is automatically filled in during website deployment.
 * logohandle - (required) unique id for this project/company.  See [Naming Guidelines](#naming-guidelines) above.
 * sort - (required) how it should be sorted in a list.  Always lowercase.
 * tags - array of tags
 * title - (required) project/company name (as short as possible)
 * website - (required) project/company website

## Metadata Links

Links to this project/company on various websites.  I'm generally interested in sites where there should be a publicly accessible logo.

 * blog
 * facebook
 * github - just the bare organization name or org/repo
 * googleplus
 * instagram
 * linkedin
 * pinterest
 * reddit
 * tumblr
 * twitter - just the bare id (no @ sign)
 * wikipedia
 * youtube

## Tools
 
