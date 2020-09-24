Contributions to this repository are greatly appreciated!

### Jump to:

[HTML formatting](#html-formatting)

[.cpanel.yml file](#cpanelyml-file)

# HTML formatting
### Jump to:

[A. Indentation and whitespace](#a-indentation-and-whitespace)

[B. Tags](#b-tags)

[C. When in doubt](#c-when-in-doubt)

## A. Indentation and whitespace
  1. Opening tags must match the indentation of closing tags.
  ```
  <p>
    Like this.
  </p>

  <p>
    Not like this.
    </p>
  ```
  The exception is when you have something like this.

  `<p> hi </p>`

  In that case the opening and closing tags will just be in the same line.

  2. Nested tags should be indented properly.
  
  ```
  <div>
    <p>
      Like this.
    </p>
  </div>

  <div>
  <p>
    Not like this.
  </p>
  </div>
  ```

  3. Use 2 spaces instead of tabs for every indentation (or set your tab to 2 spaces)

  4. Leave exactly 1 empty line of code between main sections (e.g. right before the footer)

  5. Remove all trailing whitespace.

  6. Include a newline at the end of each file.

## B. Tags
  1. Don't use <div> and <span> when there are better alternatives. 
  
  ```
  <footer> Like this. </footer>
  
  <div class="footer"> Not like this. </div>
  ```

## C. When in doubt
  1. When in doubt, match the formatting of index.html and/or ask one of the IHS GWC officers. 

# .cpanel.yml file
  1. If you add a new folder or file that's not inside a folder, update .cpanel.yml to include the folder or file. Otherwise, your changes will not show up on cPanel and the website. 

  2. If you delete a folder or file that's not inside a folder, make sure to delete it from .cpanel.yml or it will cause errors during deployment.
