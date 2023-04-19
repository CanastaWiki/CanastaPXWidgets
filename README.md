# CanastaPXWidgets
A Page Exchange package of some commonly-used widgets for the Widgets extension

# Canasta Widgets

Canasta Widgets is a package of wiki pages representing "widgets", or pages in the Widget: namespace that can be used by the MediaWiki [Widgets](https://www.mediawiki.org/wiki/Extension:Widgets) extension. It is meant to be installed via the MediaWiki extension [Page Exchange](https://www.mediawiki.org/wiki/Extension:Page_Exchange). It includes the following popular widgets:
- AdSense
- DISQUS
- Discord
- Facebook Comments
- Facebook Like Button
- SlideShare
- YouTube

Though it includes "Canasta" in its name, Canasta Widgets does not require the [Canasta](https://canasta.wiki/) MediaWiki bundle to be used.

To make use of this package within your wiki, add the following line to LocalSettings.php, below the inclusion of Page Exchange:

```php
$wgPageExchangePackageFiles[] = 'https://raw.githubusercontent.com/CanastaWiki/CanastaPXWidgets/main/page-exchange.json';
```
