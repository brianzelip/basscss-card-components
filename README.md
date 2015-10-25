# cards

``` css
/*
  
  Card

*/

.card {
  div.card--parent {
    md-col-6;
  }

  div.card {
    p2;
    bg-white;
    border;
    rounded;
  }

  h1.card--h1 {
    h2;
    mt0;
  }

  p.card--text {
    mb0;
  }
}


/*

  "To create [CARD] headers and footers,
     set padding on nested divs then
     use color styles to control appearance."

     -- http://www.basscss.com/docs/guides/ui/

*/


/*
  
  Card with header


*/

.card-with-header {
  div.card-with-header--parent {
    md-col-6;
  }

  div.card-with-header {
    overflow-hidden;
    bg-white;
    border;
    rounded;
  }

  div.card-with-header--header-h1-wrapper {
    p2;
    bg-silver;
  }

  h1.card-with-header--header-h1 {
    h2;
    m0;
  }

  div.card-with-header--body-text-wrapper {
    p2;
  }

  p.card-with-header--body-text {
    m0;
  }
}



/*
  
  Card with image lead

*/

.card-with-image-lead {
  div.card-with-image-lead--parent {
    md-col-6;
  }

  div.card-with-image-lead {
    p2;
    bg-white;
    border;
    rounded;
  }

  img.card-with-image-lead--img {
    mb2;
  }

  h1.card-with-image-lead--h1 {
    h2;
    mt0;
  }

  p.card-with-image-lead--text {
    mb0;
  }
}



/*
  
  Card with header & footer


*/

.card-with-header-and-footer {
  div.card-with-header--parent {
    md-col-6;
  }

  div.card-with-header-and-footer {
    overflow-hidden;
    bg-white;
    border;
    rounded;
  }

  div.card-with-header-and-footer--header-h1-wrapper {
    p2;
    bg-silver;
  }

  h1.card-with-header-and-footer--header-h1 {
    h2;
    m0;
  }

  div.card-with-header-and-footer--body-text-wrapper {
    p2;
  }

  p.card-with-header-and-footer--body-text {
    m0;
  }

  div.card-with-header-and-footer--footer-text-wrapper {
    p2;
    bg-darken-1;
  }

  p.card-with-header-and-footer--footer-text {
    m0;
    h5;
  }
}

```
