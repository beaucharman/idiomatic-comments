# idiomatic-comments

> Just for the record, how I like to comment my CSS, JavaScript and PHP, and similarly my HTML with consistent characteristics and structure, to maintain consistency, good communication and easy maintenance across languages.

# Idiomatic Comments

Just for the record, how I like to comment my CSS, JavaScript and PHP, and similarly my HTML with consistent characteristics and structure, to maintain consistency, good communication and easy maintenance across languages.

Inspired by the awesome [github.com/necolas/idiomatic-css](https://github.com/necolas/idiomatic-css)

### File header

```javascript

/** 
 * File Name
 * ========================================================================
 * file-name.php
 * @version 1.0 | Janurary 1st 2013
 * @package class-or-plugin-name
 * @author  Githubber | Contact @handle | Contact URL
 * @link    https://github.com/githubber/repo-url/
 * @licence license name and URL
 *
 * This is a description comment block
 * ======================================================================== */ 

```

### Function and Class Declaration

```javascript

/** 
 * Function Name
 * ========================================================================
 * function_name()
 * @param  {type} $var | variable usage description
 * @return {type}
 * 
 * This is a description / comment block about the function and it's basic 
 * usage and output. Nullam nec purus auctor purus vehicula.
 * ======================================================================== */ 

```

### Generic Comment Blocks

```javascript

/* ========================================================================
   Section comment block
   ======================================================================== */

/* Sub-section comment block
   ======================================================================== */

/**
 * This is a description comment block. Lorem ipsum dolor sit amet, 
 * consectetur adipiscing elit. Nullam nec purus auctor purus vehicula 
 * lacinia. Duis elementum arcu at diam volutpat in volutpat dolor blandit.
 *
 * and that's it...
 */ 
 
/**
 * Heading with comment block
 * ========================================================================
 * consectetur adipiscing elit. Nullam nec purus auctor purus vehicula 
 * lacinia. Duis elementum arcu at diam volutpat in volutpat dolor blandit.
 */ 

/* Single line code description */

// quick statement, description or placeholder (you code here... type of thing)
// and also used in Sass to declare what I like to refer to, 'dissolving' 
// comments.

```

**Sass**

A little more on Sass and 'dissolving' comments (The ones you don't want rendering in CSS)

```scss
// ========================================================================
// Sass section comment block
// ======================================================================== /

// Sass sub-section comment block
// ======================================================================== /

//
// Sass function / mixin
// ========================================================================
// function_name() / mixin-name()
// @param  {type} $var | variable usage description
// @return {type}
// 
// This is a description / comment block about the function / mixin / extend 
// selector name and it's basic usage and output.
// ======================================================================== / 
   
//
// Sass heading with comment block
// ========================================================================
// consectetur adipiscing elit. Nullam nec purus auctor purus vehicula 
// lacinia. Duis elementum arcu at diam volutpat in volutpat dolor blandit.
// 
   
//
// This is a description comment block for Sass. Lorem ipsum dolor sit amet, 
// consectetur adipiscing elit. Nullam nec purus auctor purus vehicula 
// lacinia. Duis elementum arcu at diam volutpat in volutpat dolor blandit.
//

```

**HTML**

Following the same practices as the above comment styles.

```html
<!--
   - Page or component title
   - ========================================================================
   - This is some description Lorem ipsum dolor sit amet, 
   - consectetur adipiscing elit. Nullam nec purus auctor purus vehicula 
   - lacinia. Duis elementum arcu at diam volutpat in volutpat dolor blandit.
   - ======================================================================== -->

<!-- ========================================================================
     Section comment block
     ======================================================================== -->
   
<!-- Sub section comment block
     ======================================================================== -->
     
<!--
   - This is a description comment block. Lorem ipsum dolor sit amet, 
   - consectetur adipiscing elit. Nullam nec purus auctor purus vehicula 
   - lacinia. Duis elementum arcu at diam volutpat in volutpat dolor blandit.
   -
   - and that's it...
--> 

<!-- Single line code description -->

```