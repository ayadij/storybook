### intro
storybook is a UI development environment for UI components

visualize different states of your UI componenets 

develop components ineractively

runs outside your app so you can develop UI components in isolation

dont have to worry about specific dependencies and requirements


---

####get started in a project:
```
cd my-project-directory
npm i -g @storybook/cli
getstorybook
```
run:
```npm run storybook```
then access storybook from browser

####storybook/react:

[docs](https://storybook.js.org/basics/guide-react/)

```npm i --save-dev @storybook/react```

add react, react-dom, and babel-core:
```npm i --save react react-dom```
```npm i --save-dev babel-core```

add to package json:
```javascript
{
  "scripts": {
    "storybook": "start-storybook -p 9001 -c .storybook"
  }
}
```
create config file

write stories

run storybook:
```npm run storybook```

---
















---
---------------

# H1
## H2
### H3
#### H4
##### H5
###### H6


Alt-H1
======

Alt-H2
------

*italicized* _emphasis_
**bold** __strong__
~~scratch this~~

   properly indented paragraphs

- unordered lists

[i am in inline-style link](google.com)
>blockquote

