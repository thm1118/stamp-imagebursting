# Introduction #

The stamp image bursting application uses particle analysis to attempt to find the bounding boxes of a stamp on the page.  The following provides some information on the procedure used.

# Details #

The following is the steps taken on a loaded image in order to determine the bounding boxes of the stamps on the page.

  * Convert the image to 8-bit indexed color
  * Translate this to a binary (black and white image)
  * Attempt to apply a despeckle algorithm to remove small specks.
  * Remove any outliers that are blobs of 5 pixels or smaller that are within 50 indexed color values
  * Invert the image colors (black becomes white and vice versa)
  * Process any internal spaces by "filling" the holes of that space.
  * Analyze the particles looking for particles that are at least 10,000 total pixels (this value can now be set in the Settings dialog)
  * Extract the calculated bounding boxes.