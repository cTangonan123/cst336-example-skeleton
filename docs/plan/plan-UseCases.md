# Use Cases: Example
[Back to TODO](/docs/plan/TODO.md)
## Table of Content
- [Click Event on `x` on view `y`](#use-case-1-click-event-on-x-on-view-y)
- [Click Event on `w` on view `z`](#use-case-2-click-event-on-w-on-view-z)

---
### Use Case 1: click event on `x` on view `y`
1. user clicks `x` button on `y` view
2. `client.js` picks up click event of `x`
3. `client.js` makes api call to `server`
4. `server` response ok sent json back to `client.js`
    1. server response not ok sent error to `client.js`
    2. `client.js` handles error, no changes made
5. response ok, `client.js` parses `JSON` and populates view with `new` elements.

### Use Case 2: click event on `w` on view `z`
1. user clicks `z` button on `w` view
2. `client.js` picks up click event of `z`
3. `client.js` makes api call to `server`
4. `server` response ok sent json back to `client.js`
    1. server response not ok sent error to `client.js`
    2. `client.js` handles error, no changes made
5. response ok, `client.js` parses `JSON` and replaces `old` elements view with `new` elements.
