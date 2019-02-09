# FlikrInfinteImageSearch

This is an android application that uses Flickr Image Search API and shows the result in 3 colum infinte scrollable View.
There also a possibility to select then number of images to be loaded at once
The app supports endless scrolling automatic requesting and displaying of images
More Images are loaded when the user scrolls to the bottom of the view.

The project has been divided into different activities and fragments according to the requirement.
Initially the splash screen activity pops up for 5 seconds.
The GalleryImageActivity.java contains the code to search query and select the number of images loaded into the buffer at once.
The GalleryImageFragment is designed to divide the screen into three and load the selected number of images
ImageFragment is designed to display single image
GalleryImageItem is used to the image url
GalleryAdapter is for infinite image search
UrlManager is designed to get the url of the images in accordance with the search query
