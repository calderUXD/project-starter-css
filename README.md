# project-starter-css
A base framework made with stylus to kick of a project. 

## Contents

Below is a list of contents. It is important to include in this order for specificity rules. Each section has a _build file to include.

```js
'/01_settings'  // Contains all the base settings for the project, variables, and globals for the project.

'/02_tools'  // Global mixins and functions

'/03_resets'  // Low-specificity, far-reaching rulesets such as normalize etc.

'/04_base'  // Unclassed html element rules and styles

'/05_objects'  // Abstracted generic classed objects such as lists, media objects, buttons, tables

'/06_components'  // Complete chunks of HTML elements such as a nav component

'/07_overrides'  // High-specificity, very explicit selectors. Overrides and helper classes such as (.hide)

```

build.styl is the build file to set up the compiled style sheet.