# &lt;/> HTMx 
*HTML Extensions*

## GOALS

* Dependency-free implementation of intercooler.js-like HTML-driven AJAX functionality
* Minimalist functionality, rely heavily on built in functionality
* Support IE10+
** CSS transitions only
** Pluggable event model
* < 10k in .min form

## TODOS

* history support
  * Implement LRU
  * Issue GET to restore content if there isn't a copy locally
* polling cancellation API 
* Testing
  * polling
  * merge
  * hx-select
  * history
  * hx-boost
  * transition model for content swaps
* distribute on https://unpkg.com/
* build website with 11ty
  * landing page
  * docs page 
  * examples page (steal intercooler)
  * attributes page
  * events page
  * headers page


## Unsupported Intercooler Features

* local actions
* all request parameters
* all response headers except X-*-Trigger
* dependencies
* macros

## RESOURCES

* http://youmightnotneedjquery.com/
* http://intercoolerjs.org/docs.html
* http://intercoolerjs.org/reference.html
* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakMap
