# Online clothing library

Upload PNG, JPEG or WebP clothing images into this folder. Keep each image under 20 MB.

Then edit `catalog.json` to list the images you want in the Wardrobe gallery.
For example, after uploading a file named `black-dress.jpg`, use this catalog:

```json
{
  "items": [
    { "name": "Black dress", "file": "black-dress.jpg" }
  ]
}
```

Add another entry for each image, separated by commas. Filenames are case-sensitive.
Commit both the image and catalog change. Refresh the site after GitHub Pages finishes deployment.
These files are public. Your private character library belongs on your device.
The site loads the catalog on opening, and includes selected clothing image data in scene exports and backups.

