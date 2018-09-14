# Simplenote for Electron

![Screenshot](https://en-blog.files.wordpress.com/2018/09/screenshot-1.png)

A Simplenote [React](https://reactjs.org/) client packaged in [Electron](https://electronjs.org/). Learn more about Simplenote at [Simplenote.com](https://simplenote.com).

## Running

1. Clone the repo: `git clone https://github.com/Automattic/simplenote-electron.git`
2. `npm install` _or_ `docker-compose up install` (if Docker installed)
3. `npm start` _or_ `docker-compose up dev` (if Docker installed)
4. Open http://localhost:4000.
5. Sign up for a new account within the app. Use the account for **testing purposes only** as all note data will be periodically cleared out on the server.

_Note: Simplenote API features such as sharing and publishing will not work with development builds._

## Electron

1. Run `npm run build`
2. Run `npm run electron`

You can also pass along the `--devtools` option (`npm run electron -- --devtools`) to open the developer tools.

## Coding Guidelines

Please adhere to the same guidelines as found in [wp-calypso](https://github.com/Automattic/wp-calypso/blob/master/docs/coding-guidelines.md).

## Dependencies

- [node-simperium](https://github.com/Simperium/node-simperium) for Simperium syncing.
- [ReactJS](https://reactjs.org/) for UI.
- [Electron](https://electronjs.org/) for wrapping the JavaScript application.
