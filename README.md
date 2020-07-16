## Get started

```
import React from 'react'
import ReactDOM from 'react-dom'

import { ThemeProvider, Text } from 'evergreen-ui'

import theme from './custom-theme'

const CustomThemeProvider = (props) => (
  <ThemeProvider value={theme}>
    {props.children}
  </CustomThemeProvider>
)

ReactDOM.render(<CustomThemeProvider><Text>Hello</Text></CustomThemeProvider>, document.getElementById('root'))

export default MyThemeProvider
```

### Notes
Combatible with evergreen v4 - May not be compatible with future versions