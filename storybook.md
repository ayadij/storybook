### intro
UI development environment 

for UI components

visualize different states of your UI componenets 

develop components ineractively

"component explorer"

runs outside your app so you can develop UI components in isolation

dont have to worry about specific dependencies and requirements

- [storybook home](https://storybook.js.org/)
- [storybook docs](https://storybook.js.org/basics/introduction/)
- [storybook examples](https://storybook.js.org/examples/)
- [storybook live example](https://storybooks-official.netlify.com/?selectedKind=ui%2FMenuItem&selectedStory=default&full=0&addons=1&stories=1&panelRight=0&addonPanel=storybook%2Fstories%2Fstories-panel)

---

pain points without storybook: app reloads, looses context (ex: input references), makes network requests

### PROS:
- makes you aware of state early on
- collaberate in ease
- integrated into your app but runs outside of it
- develop component in isolation
- focus on component without having to manipulate a larger application
- no worries about dependencies and requirements
- see UI changes online on the app without leaving the browser
- flexibility
- quick iteration
- reusability
- documentation for collaberating cross funtional teams

### HOW:
simple to implement. navigate to project. cli commands. install storybook/react. add corresponding scripts. will compile everyting in their own webpack and dev set up. offer a localhost to see gooie

make modifications to import your webpack into theirs

write stories to get components into their gooies

stories look a lot like like test specs

### WORKFLOW:
- frontend developers can continue to make progress even when details change 
- other teams will not be a stopper
- easy for new devs to jump into without knowing everything about the whole app
- help designers context switch over weeks of time

_"gooie"_

---

#### get started in a project:
```
cd my-project-directory
npm i -g @storybook/cli
getstorybook
```
run:

```npm run storybook```
then access storybook from browser

#### storybook/react:

[docs](https://storybook.js.org/basics/guide-react/)

```npm i --save-dev @storybook/react```

add react, react-dom, and babel-core:
```
npm i --save react react-dom
npm i --save-dev babel-core
```

add to package json:
```javascript
{
  "scripts": {
    "storybook": "start-storybook -p 9001 -c .storybook"
  }
}
```
create config file:

```getstorybook``` CLI generates 5 config files
- .storybook/config.js
- .storybook/webpack.config.js
- ./package.json
- ./stories/index.js
- ./webpack.config.js

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

