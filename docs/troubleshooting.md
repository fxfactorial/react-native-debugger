# Troubleshooting

## React Inspector get stuck at "Connecting to React…" for RN ^0.43 ([#45](https://github.com/jhen0409/react-native-debugger/issues/45))

It usually on Android, the problem is related to `requestIdleCallback` API (try to check if it not work on debug mode).

This issue have been fixed in `react-devtools-core@^2.3.0`, please ensure the version is correct in your React Native project (Note that it's dependency of `react-native`). Feel free to file an issue if it still not working.

## Console thrown a lot of errors when I use React Inspector on Android

If you're experiencing the issue like [this comment of #84](https://github.com/jhen0409/react-native-debugger/issues/84#issuecomment-304611817), this issue have been fixed in `react-devtools-core@^2.3.0`, please ensure the version is correct in your React Native project (Note that it's dependency of `react-native`).
