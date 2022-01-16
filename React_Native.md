# ReactNative

- Expo Go
    
      - React_Native 코드가 들어가는 부분을 제외한 나머지 Structure들을 구성해줌으로써 간편하게 코드를 실행할 수 있도록 해줌
    
    - 주로 Prototype을 생성할때 사용
    
    Desktop 💻
    
    ```bash
    npm install --global expo-cli
    ```
    
    핸드폰 📱
    
    Install ExpoGO App
    
- Components
    
    ## React_Native Components
    
    ```jsx
    import { StyleSheet, Text, View } from 'react-native';
    ```
    
    - 이런 StyleSheet, Text와 같은 Component들은  react native 공식 홈페이지에서 더 확인할 수 있음
    - 이전 버전들에는 다양한 component들이 존재했지만, 최신 버전들에선 많이 사라짐
        - 많은 component를 지원하는게 어렵기 때문!
        - 따라서 React_Native는 매우 필수적인 component들만 남겨둠

## View

```jsx
<View style={flexDirection: "row"}> </View>
```

- React_Native는 display block grid와 같은 개념X
- display flex 이용!
