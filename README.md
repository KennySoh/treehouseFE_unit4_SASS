# A Web Style Guide & The use of Sass. 
A style guide are used defined the look and feel of user interface elements on a site. Sass is used to streamline the css creation. 

***
- SASS
  - Introduction of vairables 
  ```
  /*Variables*/
  $color-primary:#58e1c1;
  $color-secondary:#51ddfc;
  $color-text:#777;

  $color-default:#51ddfc;
  $color-success:#63cc82;
  $color-error:#e4757a;
  $color-warning:#fd7856;
  $color-info:#927bc1;

  $color-col-1: #927bc1;

  $color-img-frame:#ccc;

  $breakpoint-med:768px;
  ```
  - Seperate Your Stylesheet into Partials
  ```
  //Utilities
  @import 'utilities/variables',
    'utilities/mixins',
    'utilities/functions',
    'utilities/helpers';

  //Base Styles
  @import 'base/reset',
    'base/base';

  //Laout Styles
  @import 'layout/containers',
    'layout/header',
    'layout/card',
    'layout/footer';
  ```
  - The use of mixins to adhere to DRY concepts
***

To explore the project visit the Github Page: https://kennysoh.github.io/treehouseFE_unit4_SASS/

## A sample of the project
|![images](https://github.com/KennySoh/treehouseFE_unit4_SASS/blob/master/sample-pic.png) |

