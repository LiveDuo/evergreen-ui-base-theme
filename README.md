## Get started

```
import React from 'react'
import ReactDOM from 'react-dom'

import { ThemeProvider, Text } from 'evergreen-ui'

import theme from './custom-theme'

const App = () => (
  <ThemeProvider value={theme}>
    <Text>Hello</Text>
  </CustomThemeProvider>
)

ReactDOM.render(App, document.getElementById('root'))
```

### Notes
Combatible with evergreen v4 - May not be compatible with future versions