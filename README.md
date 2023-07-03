# AquiTransit - LAquila Bus App

A mobile application developed for LAquila, Italy, aimed at providing information and services related to bus transportation. The app is available in two versions: one developed in Ionic and the other in React Native.

## Collaborators

This project has been developed in collaboration with the following contributors:

- [Halcatraz](https://github.com/Halcatraz)
- [kingajohanna](https://github.com/kingajohanna)
- Kolja Eggers

## Requirements

To set up the development environment, follow these steps:

1. Install Node.js 18 from [here](https://nodejs.org/en/download).

### Setup for Windows

- For Android: Follow the instructions [here](https://reactnative.dev/docs/environment-setup?os=windows&platform=android).
- For iOS: Unfortunately, running iOS is not supported on Windows.

### Setup for Mac

- For Android: Follow the instructions [here](https://reactnative.dev/docs/environment-setup?os=macos&platform=android).
- For iOS: Follow the instructions [here](https://reactnative.dev/docs/environment-setup?os=macos&platform=ios).

## Installation

1. Install npm packages by running `npm i` (Only on Mac).
2. Install pods for iOS by running `npx pod-install`.

## Usage

- Start only the Metro server: `npm run start` (Use this if the `node_modules` didn't change and the application is already installed on the test device).
- Android: Run `npm run android` (Only on Mac).
- iOS: Run `npm run ios`.

## Development Packages

### Material UI

We use the Material UI package to create components with predefined styles. For more information, refer to the [official documentation](https://www.react-native-material.com/docs/getting-started).

## Directories

The project directory structure is organized as follows:

- **components**: Contains reusable components such as buttons, headers, and texts.
- **navigation**: Contains the navigation logic. If there is a registration flow, a new navigator should be created here.
- **screens**: Contains the screens of the application. Screens render or contain the components.
- **types**: Contains types and interfaces, such as API call definitions.
- **api**: Contains the actual API calls.
- **stores**: Contains stores to store data used across multiple screens.
- **constants**: Contains helper functions and constants, such as regex checks, for use in screens/components.

Please refer to the specific directories for more details on each component.

## License

This project is licensed under the [MIT License](LICENSE).
