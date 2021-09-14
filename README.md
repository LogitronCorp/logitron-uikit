# LogiTron-Superior UIkit

[![Version](https://img.shields.io/npm/v/logitron-uikit)](https://www.npmjs.com/package/logitron-uikit) [![Size](https://img.shields.io/bundlephobia/min/logitron-uikit)](https://www.npmjs.com/package/logitron-uikit)

LogiTron-Superior UIkit is a set of React components and hooks used to build pages on LogiTron-Superior's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add logitron-uikit`

## Setup

### Theme

Before using Pancake UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from 'logitron-uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from 'logitron-uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.
