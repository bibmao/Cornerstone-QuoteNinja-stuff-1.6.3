# Changelog

## Draft

## 1.6.3 (2017-03-28)
- `stencil.conf.js` was refactored to support webpack2 builds [961](https://github.com/bigcommerce/cornerstone/pull/961)
- Load amp social share JS only when we have share icons enabled. [#968](https://github.com/bigcommerce/cornerstone/pull/968)
- Escape html for product summaries in product list view [#980](https://github.com/bigcommerce/cornerstone/pull/980)
- Add `customized_checkout` feature to features list [#974](https://github.com/bigcommerce/stencil/pull/974)
- Fixed AMP Carousel alignment on product view [#982](https://github.com/bigcommerce/cornerstone/pull/982)
- Remove footer scripts from the amp-iframe used to render product options for stores using AMP [#983](https://github.com/bigcommerce/cornerstone/pull/983)

## 1.6.2 (2017-03-15)
- Fix a bug that was not updating price and weight when an option is selected [#963](https://github.com/bigcommerce/cornerstone/pull/963)

## 1.6.1 (2017-03-14)
- Fix a bug that was preventing opening the cart preview modal [#960](https://github.com/bigcommerce/cornerstone/pull/960)

## 1.6.0 (2017-03-13)
- Google AMP support for product and category pages [#946](https://github.com/bigcommerce/cornerstone/pull/946)
- Expose `language` object on the checkout page [#910](https://github.com/bigcommerce/cornerstone/pull/910)
- Update package.json to disambiguate Stencil and Cornerstone [#943](https://github.com/bigcommerce/cornerstone/pull/943)
- Added support up to 8 levels for category menu depth [#939](https://github.com/bigcommerce/cornerstone/pull/939)
- Implement lazyloading for product card images to improve above-the-fold rendering [#944](https://github.com/bigcommerce/cornerstone/pull/944)
- Print a readable error instead of dumping the whole error object to the console [#950](https://github.com/bigcommerce/cornerstone/pull/950)
- Fixed homepage featured products floating left and unecessarily wrapping to next row [#948](https://github.com/bigcommerce/cornerstone/pull/948)
- Add google recaptcha v2 support to cornerstone. [#951](https://github.com/bigcommerce/cornerstone/pull/951)
- Added order confirmation template page [#949](https://github.com/bigcommerce/cornerstone/pull/949)
- Added theme editor setting for product display mode (grid vs list view) [#941](https://github.com/bigcommerce/cornerstone/pull/941)

## 1.5.3 (2017-02-23)
- Show 'Write a Review' link for mobile [#922](https://github.com/bigcommerce/cornerstone/pull/922)
- Update text input for product review comment to be multiline so it's not too small to be usable [#921](https://github.com/bigcommerce/cornerstone/pull/921)
- Add a larger view of a swatch image when option is hovered over on the product page [#923](https://github.com/bigcommerce/cornerstone/pull/923)
- Fixes an issue with file upload button not properly displaying in IE [#925](https://github.com/bigcommerce/cornerstone/pull/925)
- Make sure product review email links automatically pop the review form [#928](https://github.com/bigcommerce/cornerstone/pull/928)
- Fixes an issue where search results would incorrectly state there were no results when there were results visible [#934](https://github.com/bigcommerce/cornerstone/pull/934)
- Update BC logo sprite to use current BC logo [#931](https://github.com/bigcommerce/cornerstone/pull/931)
- Fix z-index for product sale badges so they aren't above the menu [#926](https://github.com/bigcommerce/cornerstone/pull/926)
- Auto-expand product videos on the product page if the product has at least one video [#935](https://github.com/bigcommerce/cornerstone/pull/935)
- Fix an issue with special characters in search results for content pages [#933](https://github.com/bigcommerce/cornerstone/pull/933)
- Fix an issue with special characters in carousel text [#932](https://github.com/bigcommerce/cornerstone/pull/932)
- Remove an unnecessary and confusing option in theme editor [#927](https://github.com/bigcommerce/cornerstone/pull/927)
- Fix an issue where required product list options would display an invalid "none" choice [#929](https://github.com/bigcommerce/cornerstone/pull/929)
- Remove unused variable causing js error with search in the nav [#938](https://github.com/bigcommerce/cornerstone/pull/938)
- Add settings to theme editor schema to customize Optimized Checkout discount banners [#924](https://github.com/bigcommerce/cornerstone/pull/924)
- Update Optimized Checkout discount banners default values per theme variation [#942](https://github.com/bigcommerce/cornerstone/pull/942)

## 1.5.2 (2017-02-14)
- Added a setting to theme editor schema to show/hide the homepage carousel [#909](https://github.com/bigcommerce/cornerstone/pull/909)
- Prevent carousel images from being cut off on large screens by adding a new setting to theme editor schema [#909](https://github.com/bigcommerce/cornerstone/pull/909)
- Add schema description specifying that social media icons must be set up to see them [#920](https://github.com/bigcommerce/cornerstone/pull/920)
- Show account creation links only if it is enabled in store settings [#917](https://github.com/bigcommerce/cornerstone/pull/917)
- Add GeoTrust SSL Seal Toggle [#903](https://github.com/bigcommerce/cornerstone/pull/903)

## 1.5.1 (2017-02-07)
- Fix an issue with a horizontal scroll bar showing in theme editor [#915](https://github.com/bigcommerce/cornerstone/pull/915)
- Hide Gift Certificates when the setting is disabled in the control panel [#914](https://github.com/bigcommerce/cornerstone/pull/914) & [#916](https://github.com/bigcommerce/cornerstone/pull/916)
- Fix an issue with a close button on the quick search modal on mobile [#918](https://github.com/bigcommerce/cornerstone/pull/918)
- Adding CHANGELOG.md [#919](https://github.com/bigcommerce/cornerstone/pull/919)