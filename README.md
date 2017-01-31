# react-native-fade-in-view
> A simple and lightweight RN component that fades in its children

## Install
`yarn add react-native-fade-in-view` or `npm install react-native-fade-in-view --save`

## API
### `onFadeComplete`
A function that is called when the fade animation completes

### `duration || 500`
The duration of the fade animation, 500ms by default

### `style`
Style to be given to the view

## Usage
```javascript
import FadeInView from 'react-native-fade-in-view';

const myFadeInComponent = () => (
  <FadeInView
    duration={750}
    style={{ alignItems: 'center' }}
    onFadeComplete={() => alert('Ready')}
  >
    <Text>This view will fade in nicely</Text>
  </FadeInView>
);
```
