# cst336-example-skeleton
for our group project, implementing documentation, so single source to find our planning

---
## Documentation Example
- [This is an example](/docs/example.md)
- [This links to a README.md in the exampleFolder](/docs/exampleFolder/)
- [This links to the someOtherDoc.md in the exampleFolder](/docs/exampleFolder/someOtherDoc.md)

## Table of Contents
- [TODO's for meeting](/docs/plan/TODO.md)
- Diagrams needed by:
  - [Entity Relationship Diagram](/docs/plan/diagram-ER.md)
  - [State Diagram](/docs/plan/diagram-State.md)
  - [UI Diagram](/docs/plan/diagram-UI.md)
  - [Views Diagrams](/docs/plan/diagram-views.md)

---
## Basic Syntax for Markdown:
# Heading 1
`# Heading 1`
## Heading 2
`## Heading 2`
...
**Some Bold Text**
`**Some Bold Text**`

*Some Italic Text*
`*Some Italic Text*`

==Some Highlighted Text==
`==Some Highlighted Text==`

~~Some Strikethrough Text~~
`~~Some Strikethrough Text~~`

## How to link documents
`[what you want displayed](Path/to/doc)`
- [what you want displayed](/docs/example.md)

## How to include an image in markdown
`![prefix link with exclamation point](Path/to/doc)`
![prefixed with exclamation](/docs/img/exampleImage.jpeg)

## How to Write `code` in markdown
for language codes refer to 
\`\`\`{language}
{your code here}
\`\`\`

### Example
javascript
```js
app.get('index', async(req, res) => {
  res.send("hello world");
})
```
html
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <h1>Hello World!</h1>
</body>
</html>

```
css
```css
.example {
  width: 100px;
}
```



---