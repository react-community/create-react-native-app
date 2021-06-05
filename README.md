<!-- Title -->

<p align="center">
  <a href="https://github.com/expo/examples">
    <img src="./.gh-assets/header.png" height="128">
    <h1 align="center">Create React Native App</h1>
  </a>
</p>

<!-- Header -->

<p align="center">
  <b>The fastest way to create universal React Native apps</b>
  <br />

  <p align="center">
    <!-- iOS -->
    <img alt="Supports Expo iOS" longdesc="Supports Expo iOS" src="https://img.shields.io/badge/iOS-000.svg?style=flat-square&logo=APPLE&labelColor=999999&logoColor=fff" />
    <!-- Android -->
    <img alt="Supports Expo Android" longdesc="Supports Expo Android" src="https://img.shields.io/badge/Android-000.svg?style=flat-square&logo=ANDROID&labelColor=A4C639&logoColor=fff" />
    <!-- Web -->
    <img alt="Supports Expo Web" longdesc="Supports Expo Web" src="https://img.shields.io/badge/web-000.svg?style=flat-square&logo=GOOGLE-CHROME&labelColor=4285F4&logoColor=fff" />
  </p>
  <p align="center">
    <a href="https://packagephobia.now.sh/result?p=create-react-native-app">
      <img alt="the best way to bootstrap a react native app" longdesc="the best way to create a react native app" src="https://flat.badgen.net/packagephobia/install/create-react-native-app" />
    </a>
  </p>
  
</p>

<!-- Body -->

```sh
npx create-react-native-app
```

Once you're up and running with Create React Native App, visit [this tutorial](https://reactnative.dev/docs/tutorial) for more information on building mobile apps with React.

<p align="center">
  <img align="center" alt="Product: demo" src="./.gh-assets/crna.gif" />
</p>

## Features

- Native project ready to be built on to your device.
- Support for unimodules and auto-linking.
- OTA updates, and Gestures out of the box.
- Full support for React Native web.
- Plug-n-play custom templates.
- Works with the Expo Client app.

## Usage

- `npx create-react-native-app` Create a new native React app.
- `yarn ios` -- (`expo run:ios`) Build the iOS App (requires a MacOS computer).
- `yarn android` -- (`expo run:android`) Build the Android App.
- `yarn web` -- (`expo start:web`) Run the website in your browser.

### Templates

By default you create a [bare-workflow React](https://docs.expo.io/bare/exploring-bare-workflow/) project with support for iOS, Android, and web. You can opt to use an example project instead by selecting the "Templates from ..." option. Custom templates can be used with `--template <Example Name or GitHub URL>` option.

- Use an [example](https://github.com/expo/examples): `npx create-react-native-app -t with-typescript`
- Use a custom template: `npx create-react-native-app --template https://github.com/someone/my-react-starter` -- Only works with GitHub repos on the master branch.
- All examples can be modified in the [expo/examples](https://github.com/expo/examples) repo.

## Sections

- [Usage with Expo Client App](#usage-with-expo-client-app)
- [Support and Contact](#support-and-contact)
- [FAQs](#faqs)
- [Contributing](#contributing)

## Usage with Expo Client App

Expo Client enables you to work with all of the [Components and APIs](https://facebook.github.io/react-native/docs/getting-started) in `react-native`, as well as the [JavaScript APIs](https://docs.expo.io/versions/latest) that the are bundled with the Expo App.

Expo Client supports running any project that doesn't have custom native modules added.

- Download the "Expo Client" app from the Play Store or App Store.
- Start your project with Expo
  - Install the CLI `npm i -g expo-cli`
  - Start the project `expo start`
- Open the project:
  - Sign in to expo and the project will appear in the app.
  - Or point your phone's camera at the QR code in the terminal (press "c" to view it).

## Support and Contact

If you're having issues with Create React Native App, please make sure:

- The issue is not covered in the [Expo Docs](https://docs.expo.io/versions/latest/)
- There is not already an [open issue](https://github.com/expo/expo-cli/issues) for your particular problem

If you've checked the documentation and currently open issues, please either [open a new GitHub issue](https://github.com/expo/create-react-native-app/issues/new) or ask a question on [Expo forums](https://forums.expo.io/c/help).

## Contributing

Please see [Contributing guide](https://github.com/expo/expo-cli/blob/master/CONTRIBUTING.md) in the Expo CLI monorepo for instructions on contributing to Expo CLI.

### Attribution

The examples feature was inspired by the `templates` system of [create-next-app](https://github.com/zeit/next.js/tree/canary/packages/create-next-app) by the [Vercel](https://vercel.com/) team.

## Related

- [Ignite CLI](https://github.com/infinitered/ignite) by [Infinite Red](https://infinite.red/)
- [Expo CLI](https://github.com/expo/expo-cli) by [Expo team](https://expo.io)
- [React Native Community CLI](https://github.com/react-native-community/cli) by members of [the React Native community](https://github.com/orgs/react-native-community/people)

<!-- Footer -->

## Contributors ✨

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->

[![All Contributors](https://img.shields.io/badge/all_contributors-6-orange.svg?style=flat-square)](#contributors-)

<!-- ALL-CONTRIBUTORS-BADGE:END -->

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://twitter.com/baconbrix"><img src="https://avatars1.githubusercontent.com/u/9664363?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Evan Bacon</b></sub></a><br /><a href="https://github.com/expo/create-react-native-app/commits?author=EvanBacon" title="Code">💻</a> <a href="https://github.com/expo/create-react-native-app/commits?author=EvanBacon" title="Documentation">📖</a> <a href="#design-EvanBacon" title="Design">🎨</a> <a href="#maintenance-EvanBacon" title="Maintenance">🚧</a> <a href="https://github.com/expo/create-react-native-app/pulls?q=is%3Apr+reviewed-by%3AEvanBacon" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://expo.io"><img src="https://avatars2.githubusercontent.com/u/90494?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Brent Vatne</b></sub></a><br /><a href="https://github.com/expo/create-react-native-app/commits?author=brentvatne" title="Code">💻</a> <a href="https://github.com/expo/create-react-native-app/commits?author=brentvatne" title="Documentation">📖</a> <a href="https://github.com/expo/create-react-native-app/pulls?q=is%3Apr+reviewed-by%3Abrentvatne" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="http://hamzah"><img src="https://avatars0.githubusercontent.com/u/26879042?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Hamza Halilovic</b></sub></a><br /><a href="https://github.com/expo/create-react-native-app/commits?author=hamzahalilovic" title="Code">💻</a></td>
    <td align="center"><a href="https://bycedric.com"><img src="https://avatars2.githubusercontent.com/u/1203991?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Cedric van Putten</b></sub></a><br /><a href="https://github.com/expo/create-react-native-app/commits?author=byCedric" title="Code">💻</a></td>
    <td align="center"><a href="https://twitter.com/VilleImmonen"><img src="https://avatars3.githubusercontent.com/u/497214?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Ville Immonen</b></sub></a><br /><a href="https://github.com/expo/create-react-native-app/commits?author=fson" title="Code">💻</a> <a href="https://github.com/expo/create-react-native-app/pulls?q=is%3Apr+reviewed-by%3Afson" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/friederbluemle"><img src="https://avatars0.githubusercontent.com/u/743291?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Frieder Bluemle</b></sub></a><br /><a href="https://github.com/expo/create-react-native-app/commits?author=friederbluemle" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
