# rn-cocos

Based on ReactNative JSI implementation, Auto Linking is not available yet. Some manual configuration is required

## Installation

```sh
yarn add react-native-cocos2dx@https://github.com/lxp-git/react-native-cocos2dx.git
```

## How to use

### iOS

Please follow the Hello World of Cocos project to set up the Cocos2d dependency of the project.

### Android

Cocos2d dependency has been implemented for you, but you need to manually fill in the build directory of the Cocos project and `.env` set it in the file in the project root directory `COCOS_BUILD_PATH`。

### js
```js
import { Cocos2dGlviewView } from 'react-native-cocos2dx';

// ...

<View style={{ flex: 1 }}>
  <Cocos2dxGLView />
</View>;
```

See ./example

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT
