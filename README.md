# voter-app-native
- To build apk for android with expo:


- To build .apk file

```shell
eas build -p android --profile preview
eas build -p android --profile preview --clear-cache

```

- To build .aab file


```shell
eas build --platform android
```


- To build .aab file

```shell
eas build --profile preview2

```

- To build .aab file for production

```shell
eas build -p android --profile production --clear-cache


```


- To check all package vulnerabilities and update
```shell
npx expo-doctor
npx expo install --check
```


- To Login in expo account from terminal
```shell
expo login
```


- To Login out in expo account from terminal
```shell
expo logout
```

build locally
eas build --platform android --local
