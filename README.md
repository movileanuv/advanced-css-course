# Course notes for the Advanced CSS course

* reset styles for browser
  ```css
  *,
  *::before,
  *::after {
      margin: 0;
      padding: 0;
      box-sizing: inherit;
  }
  
  body {
    box-sizing: border-box;
  }
  ```

* use relative units to define font sizes and lengths

  ```css
  html {
    font-size: 62.5%; /* 10px */
  }
  
  body {
    font-size: 1.6rem;
  }
  ```

* the 7-1 pattern:
  * `base/` basic project definitions
  * `components/` one file for each component
  * `layout/` overall layout of the project
  * `pages/` styles for specific pages
  * `themes/` when implementing different visual themes
  * `abstracts/` variables and mixins
  * `vendors/` third party css
