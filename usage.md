# Usage


### Gallery initialization

1. [Initialization gallery from file](./initialization_gallery_from_file.md);
2. [Initialization gallery programmatically](./initialization_gallery_programmatically.md);


### Launch Gallery's

Create intent and put gallery object in extras:
```
...
Intent intent = new Intent(this, ActivityGallery.class);
intent.putExtra(AGGallery.ALBUMS_BY_CATEGORY, mGallery);

startActivity(intent);
...
```





