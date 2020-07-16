# evergreen-ui-base-theme

# Get started

Combatible with evergreen v4 - May not be compatible with future versions

```
import React from 'react'
import ReactDOM from 'react-dom'

import { ThemeProvider } from 'evergreen-ui'

import theme from './custom-theme'

const CustomThemeProvider = (props) => (
  <ThemeProvider value={theme}>
    {props.children}
  </CustomThemeProvider>
)

ReactDOM.render(<CustomThemeProvider><span>Hello</span></CustomThemeProvider>, document.getElementById('root'))

export default MyThemeProvider
```