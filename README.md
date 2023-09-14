# Flipkart-navbar
# HTML Tags Explanation

This README explains the HTML tags used in the provided HTML code.

### `<!DOCTYPE html>`
- This declaration specifies the document type and version of HTML being used, which is HTML5 in this case.

### `<html>`
- The root element of an HTML document, encapsulating the entire content.

### `<head>`
- Contains meta-information about the HTML document, such as character encoding, viewport settings, and linked resources.

    - `<meta charset="UTF-8">`: Specifies the character encoding as UTF-8, which supports a wide range of characters and symbols.
    
    - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Defines the viewport settings for responsive design.

    - `<link rel="icon" href="...">`: Links to the website's favicon (shortcut icon) displayed in the browser tab.

    - `<title>...</title>`: Sets the title of the webpage, which appears in the browser's title bar or tab.

    - `<link rel="stylesheet" href="...">`: Links external CSS stylesheets to style the HTML content.

### `<body>`
- Contains the main content of the webpage, including text, images, and other elements.

### `<nav>`
- Represents a navigation menu or bar on the webpage.

    - `<div class="logo">`: A division for the website's logo and text.

        - `<img src="..." width="75px" height="20px">`: Embeds an image as the logo.

        - `<p>...</p>`: Contains text and icons.

    - `<div class="search">`: Another division for the search bar.

        - `<input type="text" placeholder="...">`: Creates a text input field for searching.

        - `<i class="fa-solid fa-magnifying-glass"></i>`: Embeds an icon for the search button.

    - `<button class="loginbtn">login</button>`: A login button.

    - Anchor tags (`<a>`) for navigation links.

### `<section>`
- Defines a section of content within the webpage.

    - `<div class="topProductNavbar_nav">`: Contains individual navigation items.

        - `<img src="..." alt="...">`: Embeds images with alt text for accessibility.

        - `<p>...</p>`: Contains text.

        - `<span><i class="fa-solid fa-angle-down"></i></span>`: Embeds an icon within a span element.

In addition to these tags, there are also various attributes, such as `href`, `class`, `width`, and `height`, used to provide additional information and styling to the HTML elements.

## ScreenShorts

The whole website is divided into two section:
### navbar Section

<img width="955" alt="fli1" src="https://github.com/bagheladarsh007/Flipkart-navbar/assets/142333682/882a034e-6e0b-40fd-9971-53a72801352e">

### Products section
<img width="960" alt="fli2" src="https://github.com/bagheladarsh007/Flipkart-navbar/assets/142333682/105c97e7-62f0-4bf7-964b-713107cff86b">


# CSS Properties Explanation

This README explains the CSS properties used in the provided CSS code.

### `*`
- This selector applies the following styles to all HTML elements, resetting the default margin and padding to zero.

### `nav`
- Styles applied to the `<nav>` element, which represents the navigation bar.

    - `background-color`: Sets the background color to `#2874f0`.
    
    - `display`: Uses flexbox to center-align and vertically align the content.
    
    - `padding`: Adds padding of `10px` on the top and bottom, `0` on the left and right.

### `.plus-color`
- Styles applied to elements with the class `plus-color`.

    - `color`: Sets the text color to `#f0dd10`.
    
    - `font-weight`: Sets the font weight to `600`.

### `.logo p`
- Styles applied to `<p>` elements within an element with the class `.logo`.

    - `color`: Sets the text color to `white`.
    
    - `position`: Adjusts the position of the element.
    
    - `top`: Moves the element `7px` up from its normal position.

### `.search`
- Styles applied to elements with the class `.search`, presumably the search bar.

    - `background-color`: Sets the background color to white.
    
    - `width`: Sets the width to `420px`.
    
    - `height`: Sets the height to `20px`.
    
    - `padding`: Adds `8px` of padding.
    
    - `margin`: Adds margin `0` on top and bottom, `15px` on left and right.
    
    - `display`: Uses flexbox to space content evenly horizontally.
    
    - `color`: Sets text color to `#2874f0`.
    
    - `border-radius`: Rounds the corners with a `3px` radius.
    
    - `box-shadow`: Adds a shadow effect.

### `.search input`
- Styles applied to `<input>` elements within an element with the class `.search`.

    - `width`: Sets the width to `380px`.
    
    - `border`: Removes the border.
    
    - `outline`: Removes the outline.
    
    - `padding`: Adds `0` padding on the top and bottom, `4px` on the left and right.

### `.loginbtn`
- Styles applied to elements with the class `.loginbtn`, presumably a login button.

    - `padding`: Adds `7px` padding on top and bottom, `40px` on left and right.
    
    - `border`: Removes the border.
    
    - `outline`: Removes the outline.
    
    - `font-weight`: Sets the font weight to `550`.
    
    - `color`: Sets the text color to `#2874f0`.

### `.navlinks`
- Styles applied to elements with the class `.navlinks`, presumably navigation links.

    - `margin`: Adds `0` margin on top and bottom, `20px` on left and right.
    
    - `font-size`: Sets the font size to `18px`.
    
    - `color`: Sets the text color to white.
    
    - `text-decoration`: Removes underlines from links.

### `.angledown i`
- Styles applied to `<i>` elements within elements with the class `.angledown`.

    - `font-size`: Sets the font size to `10px`.

### `.topProductNavbar`
- Styles applied to elements with the class `.topProductNavbar`, presumably a top product navigation section.

    - `height`: Sets the height to `110px`.
    
    - `display`: Uses flexbox to center-align content horizontally.
    
    - `justify-content`: Adds `10px` of padding on top and bottom, `50px` on left and right.
    
    - `border-bottom`: Adds a `1px` solid gray border at the bottom.

### `.topProductNavbar_nav`
- Styles applied to elements with the class `.topProductNavbar_nav`, presumably individual navigation items within the top product navigation section.

    - `width`: Sets the width to `80px`.
    
    - `cursor`: Changes the cursor to a pointer.
    
    - `flex`: Allows items to grow and shrink within their container.

### `.topProductNavbar_nav img`
- Styles applied to `<img>` elements within elements with the class `.topProductNavbar_nav`.

    - `width`: Sets the width to `64px`.
    
    - `height`: Sets the height to `64px`.

### `.topProductNavbar_nav p`
- Styles applied to `<p>` elements within elements with the class `.topProductNavbar_nav`.

    - `font-weight`: Sets the font weight to `510`.

### `.topProductNavbar_nav:hover p`
- Styles applied to `<p>` elements within elements with the class `.topProductNavbar_nav` when hovered.

    - `color`: Sets the text color to `#2874f0`.

### `.topProductNavbar_nav p span`
- Styles applied to `<span>` elements within `<p>` elements within elements with the class `.topProductNavbar_nav`.

    - `font-size`: Sets the font size to `10px`.

### Hosted link
you can see the hosted link here:   https://bagheladarsh007.github.io/Flipkart-navbar/
