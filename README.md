# OnlineAnalyze UI (Tauri + Leptos)

This is a Tauri app powered by Leptos that loads the `onlineanalyze.com` website within a native window.

## Features
- Cross-platform support for macOS and Windows
- Uses Leptos for frontend rendering
- Opens `onlineanalyze.com` inside the app's window

## Setup

### Prerequisites

- [Rust](https://www.rust-lang.org/)
- [Tauri](https://tauri.app/)
- [Trunk](https://trunkrs.dev/) (for Leptos build)

### Development

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/onlineanalyze-ui.git
    cd onlineanalyze-ui
    ```

2. Install dependencies:

    ```bash
    cargo tauri dev
    ```

### Build for Production

1. Build the app:

    ```bash
    cargo tauri build
    ```

2. The production binaries will be available in the `target/release` directory.

## License

Distributed under the MIT License. See `LICENSE` for more information.
