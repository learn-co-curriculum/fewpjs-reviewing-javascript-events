# Quiz: Reviewing JavaScript Events

???

## Reviewing JavaScript Events

?: How is scope defined?

( ) with `const` variables ( ) only in the global context ( ) only within the function block (X) where declared variables and functions are visible

?: Variables declared with \_\_\_ are block-scoped:

( ) `var` (X) `let` ( ) `function`

?: Through the scope chain, a function:

(X) has access to all variables and functions declared in its outer scope. ( ) has access to all variables and functions declared only in its inner scope. ( ) has access to all variables and functions declared in its inner and outer scopes. ( ) continues to move up the scope chain when it finds a matching identifier in the current scope.

?: In the code example here, what will `myVar` equal after `function2()` is run?

```javascript
const myVar = "Foo";
function function1() {
  const myVar = "Baz";
  console.log(myVar);
}
function function2() {
  const myVar = "Bar";
  function1();
}
function2();
```

(X) "Baz" ( ) "Foo" ( ) "Bar" ( ) undefined

?: How can an JavaScript event be defined on any DOM node?

(X) `addEventListener()` ( ) `getElementById()` ( ) `querySelector()` ( ) `click()`

?: Which of these is NOT an example of a JavaScript event?

( ) Submitting a form
(X) Calling a javascript function in the global scope
( ) Pressing a key
( ) Scrolling in the browser window

?: Which variable keyword will be hoisted?

( ) `let` ( ) `const` ( ) `def` (X) `var`

?: Which of the following is NOT true about functions?

( ) functions contain a sequence JavaScript statements.
( ) functions can be executed multiple times.
(X) functions are always executed first.
( ) functions are objects.

?: Choose the version of this function that is the best example of generalization:

(X)

```javascript
function volunteerTShirtOrder(name = "Unknown", size = "Any") {
  console.log(`${name} ordered a size ${size}`);
}
```

( )

```javascript
function volunteerTShirtOrder(name, size) {
  let name = "Octavius";
  let size = "Large";
  console.log(`${name} ordered a size ${size}`);
}
```

( )

```javascript
function volunteerTShirtOrder(x, y) {
  console.log(`${x} ordered a size ${y}`);
}
```

( )

```javascript
function volunteerTShirtOrder(name, size) {
  let name = "Unknown";
  let size = "Any";
  console.log(`${name} ordered a size ${size}`);
}
```

?: The `DOMContentLoaded` event fires at when:

( ) the CSS & JavaScript have finished loading. (X) the page's DOM is fully parsed. ( ) the page has begun loading. ( ) there is an error during the page load.

???
