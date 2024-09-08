mediawiki-extension-RelatedImages
====================

Extension:RelatedImages shows several "related images" on pages like `[[File:Something.png]]`.
These recommended images are randomly chosen from the same categories as `Something.png`.

# Configuration

Everything is optional:
```php
$wgRelatedImagesMaxCategories = 1; // Default: 3
$wgRelatedImagesMaxImagesPerCategory = 4; // Default: 3
$wgRelatedImagesIgnoredCategories = [ 'Some_category', 'Another_category' ]; // Default: []
$wgRelatedImagesThumbnailWidth = 120; // Default: 50
$wgRelatedImagesThumbnailHeight = 100; // Default: 50
```

