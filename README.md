This is a [Tauri/Next.js](https://next--tauri.netlify.app/next/mobile/) mobile template project.

Tauri mobile is currently in alpha, and the repo is meant to help you skip configuration debuging, and get you started experimenting with Tauri on Android.

You will need to have [Android studio](https://developer.android.com/studio?gclid=Cj0KCQjw06-oBhC6ARIsAGuzdw3s6DJhPCGSh90ZnGYBmYwmS6GRNs_76NItVfyx55X4SCfFoI0jgL4aAlvQEALw_wcB&gclsrc=aw.ds) installed, as well as create at least one emulator.

You will also need to use npm, as the project is set up that way. Alternatively you can set it up to use pnpm or yarn, but you'll need to change the configuration in several places, and regenerate the src-tauri/gen files (delete and run `cargo tauri android init`).

To run the project:

```bash
cargo tauri android dev
```

or

```bash
npm run tauri dev
```

Enjoy!

Feel free to contact me if you would like to contribute or suggest some changes.
