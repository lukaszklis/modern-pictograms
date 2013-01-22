# Modern Pictograms

Modern Pictograms is a typeface for interface designers and programmers. Designed in early 2011 for the Flatfile Wordpress theme, the pictograms stay sharp when used large or small. Install the OpenType file for Photoshop mockups and drop in the @font-face code into your CSS to embed them right in your Web page. Designed to work on web sites at sizes down to 18 pixels, but best at higher than 24 pixels.

[Download typefaces at Font Squirrel](http://www.fontsquirrel.com/fonts/modern-pictograms)

This repo offers developers easier usage of the icons by adding or extending (LESS/SCSS) a classname.

## Credits

John Caserta, concept and design
Special thanks to Jeremy Mickel

## Example

### HTML

    <a href="#" class="comments">9 comments</div>

### LESS

    .comments {
        .mp-chat;
    }

### SCSS

    .comments {
        @extend .mp-chat;
    }