---
id: spinner
title: Spinner
---
import useBaseUrl from '@docusaurus/useBaseUrl';

Displays a circular loading indicator.

<img alt="Spinner component " src={useBaseUrl('img/spinner.gif')} />

### Example usage:
```jsx
import { Spinner } from 'react-native-ios-kit';

<Spinner animating={this.state.loading} />
```

## Theme  
Uses following `theme` properties:
- `primaryColor` - color of the Spinner.

## Props

### `animating` (optional)  
**type:** `boolean`  
**default value:** `true`  

Whether to show or hide the indicator.

### `hidesWhenStopped` (optional)
**type:** `boolean`  
**default value:** `true`  

Whether the indicator should hide when not animating.

### `size` (optional)  
**type:** `'small' | 'large'`  
**default value:** `'small'`  

Size of the indicator.

### `theme` (optional)
**type:** [`Theme`](theme)

Custom theme for component. By default provided by the ThemeProvider.
