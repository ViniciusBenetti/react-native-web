npm install -g expo-cli v 6.3.12

npx expo init videomanager

package.json
{
  "name": "gerenciadordevideos",
  "license": "MIT",
  "version": "1.0.0",
  "main": "index.js",
  "dependencies": {
    "expo": "~52.0.46",
    "expo-status-bar": "~2.0.1",
    "react": "18.3.1",
    "react-native": "0.76.9",
    "react-dom": "18.3.1",
    "react-native-web": "~0.19.13",
    "@expo/metro-runtime": "~4.0.1"
  },
  "devDependencies": {
    "@babel/core": "^7.20.0"
  },
  "private": true
}


npx expo start --web

npx expo export --platform web
