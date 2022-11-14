# build-tools

Helpers for Vite & others for my other libraries.

## Usage

### `@ignsg/vite-build-tools`

See [packages/vite-build-tools](./packages/vite-build-tools/README.md)

## Contributing

Thanks for your interest! Just a few more steps to follow and we can get your local environment up and running.

### Setting up your repository clone

1. Install node (see package.json's `engines.node` for the version), yarn (no need for any specific version) and python (any version above/at 3)
2. Run `yarn install` to install all required dependencies
3. Run `yarn prepare-local` to prepare editor integrations (VS Code) & commit hooks

> This repo already comes with all dependencies and tools using a PnP (Plug-and-Play) zero install architecture
>
> TypeScript dependencies are kept in .yarn/cache and tool executables are inside of .tools (bundled as pre-packaged apps)

### Release

1. Run `yarn change:create` for every meaningful change (such as a new feature or bugfix) - each change will then be displayed as a separate entry in the CHANGELOG
2. A CI script automatically collects your changes and opens a PR creating a new release
3. Once the release is merged another script automatically publishes the new version
