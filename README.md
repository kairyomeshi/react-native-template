# :space_invader: React Native Template with Path Aliases Support

[![release-please](https://github.com/kairyomeshi/react-native-template/actions/workflows/release-please.yml/badge.svg)](https://github.com/kairyomeshi/react-native-template/actions/workflows/release-please.yml)

<p>
  <a href="https://github.com/kairyomeshi/react-native-template#readme">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/kairyomeshi/react-native-template/graphs/commit-activity">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
  <a href="https://github.com/kairyomeshi/react-native-template/blob/master/LICENSE">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
</p>

> A clean and minimalist React Native template with support for path aliases, for a streamlined development experience.

## :star: Features

- Supports path aliases for simpler and more readable code.
- Elegant usage directly within the [React Native CLI](https://github.com/react-native-community/cli).
- Consistent with the default React Native template.
- Minimal additional dependencies.

## 📁 Path Aliases

This template is configured to support path aliases. Path aliases allow you to avoid complex relative paths in your import statements, making your code easier to read and maintain. Here is an example of how you can use path aliases in your project:


```javascript
// Without path aliases
import MyComponent from '../../components/MyComponent';

// With path aliases
import MyComponent from '@components/MyComponent';
```

## :arrow_forward: Usage

```sh
npx react-native init MyApp --template @kairyomeshi/react-native-template
```

### Usage with older versions of React Native

#### e.g. `react-native@0.71.x`

```sh
npx react-native init MyApp --template @kairyomeshi/react-native-template@2.12.0
```

See the below table to find out which version of the template to use.

#### React Native <=> Template Version

| React Native | Template |
| ------------ | -------- |
| 0.72         | 4.\**.\* |
| 0.71         | 2.\**.\* |
| 0.70         | 1.\**.\* |

## :warning: React Native CLI

This template only works with the new CLI. Make sure you have uninstalled the legacy `react-native-cli` first (`npm uninstall -g react-native-cli`) for the below command to work. If you wish to not use `npx`, you can also install the new CLI globally (`npm i -g @react-native-community/cli` or `yarn global add @react-native-community/cli`).

If you tried the above and still get the react-native-template @kairyomeshi/native-template: Not found error, please try adding the `--ignore-existing` flag to [force npx to ignore](https://github.com/npm/npx#description) any locally installed versions of the CLI and use the latest.

Further information can be found here: https://github.com/react-native-community/cli#about

## :computer: Contributing

Contributions are very welcome. Please check out the [contributing document](CONTRIBUTING.md).

## :bookmark: License

This project is [MIT](LICENSE) licensed.
