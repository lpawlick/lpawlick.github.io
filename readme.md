# Documentation Website

This website contains the documentation for all my projects. \
Each project has a subfolder in [projects](/projects) containing all the information about each project. \
Every project has a github action that builds the documentation on push and pushes the changes to this repository.
The live documentation can be found at [docs.pawlick.dev](https://docs.pawlick.dev).

## Currently listed projects

### [Dash Google Picker](https://docs.pawlick.dev/projects/dash_google_picker)

The Dash Google Picker is a [Dash](https://plotly.com/dash) component designed to seamlessly integrate Google's Picker API with Dash applications.
With this module, developers can easily implement Google Picker functionality into their Dash applications, allowing users to select files from their Google Drive account.
More information can be found in the [Google Picker Overview](https://developers.google.com/drive/picker/guides/overview).

### [inochi2d](https://docs.pawlick.dev/projects/inochi2d)

A pure Rust implementation of [Inochi2D](https://inochi2d.com), the realtime 2D puppet animation framework.
This is currently done using [serde\_json](https://crates.io/crates/serde_json) for parsing, as well as [GLFW](https://www.glfw.org) and [glow](https://crates.io/crates/glow) for the rendering, using OpenGL ES 2.0.

### [stable-diffusion-webui model notes](https://docs.pawlick.dev/projects/sd-webui-model-notes)

This is an extension for the [AUTOMATIC1111 webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui), which enables the creating, editing and deleting of notes for stable diffusion models, embeddings, hypernetworks and LoRAs right within the generation interface. Additionally it allows to downloading notes and import or export them in a variety of formats.

### [Universal Upgrade Library Python (UULPY)](https://docs.pawlick.dev/projects/uulpy)

A library that handles the internals of clicker/upgrade games, like the upgrades, the resources, and the save file. It is currently under development and not all features are implemented yet.
