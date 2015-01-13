Gruntyplate
===========

## Modernizr

  ```
  grunt modernizr
  ```

  This task will search your JS and CSS for any modernizr tasks defined and build a custom build based on this.  If for some reason a test is not defined in your JS/CSS and you want to add it, add it to the `tests` array in the modernizr task config. 

  Note: This will not automatically update on watch.  You will need to re-run the grunt modernizr task.

## Compass
  Compass is configured to work with Sassyplate.  

## Combine Media Queries
  Combine matching media queries into one media query definition. Useful for CSS generated by preprocessors using nested media queries.
