# CloudCraft DIY Bug Fixer

This is a Chrome extension that allows you to apply custom Javascript and CSS in CloudCraft in cases where you are encountering a UI bug that is slowing you down and has not been formally fixed yet.

## Installation

To enable, go to `chrome://extensions` in your browser and enable developer mode. Click **Load unpacked extension...** and select the directory where this is stored.

## Modifying Javascript

The custom Javascript that will be applied can be found at `js/content.js`. Any code you add to this file will be run on each page load after any other Javascript on the page.

## Modifying CSS

The custom CSS that will be applied can be found at `css/content.css`. Any code you add to this file will be run on each page load after other CSS files have been loaded.

> You may need to apply `!important` to CSS rules you add this way. If you're trying to apply a style and it's not showing up correctly, try adding that.

## Applying Changes

If you make changes to the JS or CSS files, you will need to reload the extension before they will be applied to the page. You can do this by visiting the `chrome://extensions` page, finding the **CloudCraft DIY Bug Fixer** extension, and clicking the reload button (a circular arrow in the bottom right). You will also need to refresh the page in CloudCraft since content changes are applied on page load.

## Reporting Bugs for Real

See a bug that you can't fix with custom JS/CSS? Click the extension icon in your browser - there's a link to the bug form so that we can get these issues fixed in a more permanent fashion.

## More Info

Feel free to open PRs if you add JS/CSS others may find useful. If you're having an issue, chances are someone else is too so please share 😎
