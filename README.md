This is a [Tauri/Next.js](https://next--tauri.netlify.app/next/mobile/) mobile template project.

Tauri mobile is currently in alpha, and the repo is meant to help you skip configuration debuging, and get you started experimenting with Tauri on Android.

## Prerequisites

First make sure you have the [prerequisites](https://next--tauri.netlify.app/next/guides/getting-started/prerequisites) for your platform.

When you set the environment variables (at least on Windows) make sure to `restart` your computer.

You will also need to use `npm`, as the project is set up that way. Alternatively you can set it up to use pnpm or yarn, but you'll need to change the configuration in several places, and regenerate the src-tauri/gen files (delete and run `cargo tauri android init`). 

## Running the project

```bash
cargo tauri android dev
```

or

```bash
npm run tauri dev
```

Enjoy!

Feel free to contact me if you would like to contribute or suggest some changes.
