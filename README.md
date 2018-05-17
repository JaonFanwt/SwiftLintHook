# SwiftLintHook
[ SwiftLintHook] provides tools which enable you to commit Swift code to a git repository using a unified style format.

## Installation
```
yarn add --dev swiftlinthook
```
or
```
npm install --save-dev swiftlinthook
```

Once the package is installed in your project, you just need to configure it by adding a `lint-staged` script which will re-run the script whenever you commit Swift code to a git repository:
```
  "lint-staged": {
    "*.swift": "./node_modules/swiftlinthook/swiftlinthook"
  },
```

## Configuration
The path of the configuration file:
```
./ios/.swiftlint.yml
```

## SwiftLint
[SwiftLint](https://github.com/realm/SwiftLint).