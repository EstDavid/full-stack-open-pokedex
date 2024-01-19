# About the project

This project consists of a mobile app coded with TypeScript and using React Native

# Linting, testing and building tools

## Linting

**ESLint** will be used for linting

## Type checking

Since the code will be written in **TypeScript**, all variables will be type checked. TypeScript's strict mode will be set to ON, and the use of the type _any_ will be allowed only in exceptional cases.

## Testing

Unit testing will be made with the **Jest** testing framework.
Testing of components will be made using React's **Test renderer** and the **React Native Testing Library**
**Detox** will be used for End-to-End tests

## Building

The builds of the app, both for Android and for iOS will be made using Expo's EAS CLI.

# Alternatives to Jenkins and GitHub Actions for setting up the CI

## Bitrise

[Bitrise](https://app.bitrise.io/cli/) offers mobile first features. It's cloud based and supports React Native.

## Other CI alternatives

Here is a handful of other CI solutions to consider:

- TeamCity
- CircleCI
- TravisCI
- GitLab CI
- Bamboo

# Cloud based setup

We will go for a cloud based setup due to the following reasons:

- We are a small team and don't foresee a need for a robust self hosted setup
- We want to focus on the code and don't have any expert in the group who can take care of the server setup
- We estimate that we can afford slow builds without impacting critically our planning
