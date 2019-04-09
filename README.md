## Quiz: Reviewing JavaScript Events

???

# Reviewing JavaScript Events

?: How is scope defined?

(X) where declared variables and functions are visible
() with `const` variables
() only in the global context
() only within the function block

?: Variables declared with ___ are block-scoped:

(X) `let`
() `var`
() `function`

?: Through the scope chain, a function:

(X) has access to all variables and functions declared in its outer scope.
() has access to all variables and functions declared only in its inner scope.
() has access to all variables and functions declared in its inner and outer scopes.
() continues to move up the scope chain when it finds a matching identifier in the current scope.

?: In the code example here, what will `myVar` equal when `function2()` is run?

```javascript
const myVar = 'Foo';
function function1 () {
  const myVar = 'Baz'
  console.log(myVar);

}
function function2 () {
  const myVar = 'Bar';
  function1();
}
function2()
````

(X) Baz
() Foo
() Bar
() undefined

?: How can an JavaScript event be defined on any DOM node?

(X) `addEventListener()`
() `getElementById()`
() `querySelector()`
() `click()`

?: What are examples of JavaScript events?

[X] Submitting a form
[X] Pressing a key
[X] Scrolling in the browser window
[] Clicking the browser’s “back” button

?: Which keyword should not be used in order to avoid potential issues from hoisting?

(X) `var`
() `let`
() `const`
() `function`

?: A function is an object that:

[X] contains a sequence JavaScript statements.
[X] can be executed multiple times.
[] contains a variable.
[] is always executed first.

?: How would you best generalize this function using parameters and arguments?

(X)
```javascript
function volunteerTShirtOrder(name=”Unknown”, size=”Any”) {
  console.log(`${name} ordered a size ${size}`);
}
```
()
```javascript
function volunteerTShirtOrder(name, size) {
  let name = "Octavius";
  let size = "Large";
  console.log(`${name} ordered a size ${size}`);
}
```
()
```javascript
function volunteerTShirtOrder(name, size) {
  console.log(`${name} ordered a size ${size}`);
}
```
()
```javascript
function volunteerTShirtOrder(name, size) {
  let name = "Unknown";
  let size = "Any";
  console.log(`${name} ordered a size ${size}`);
}
```

?: The `DOMContentLoaded` event fires at when:

(X) your page's DOM is fully parsed.
() the CSS, JavaScript) have finished loading.
() the page has begun loading.
() there is an error during the page load.

???
