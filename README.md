# Lil' Yew Rust App

This project is a basic experiment with the Yew framework in Rust, aimed at exploring and understanding the capabilities of building web applications using Rust.

## Overview

Yew is a modern Rust framework for creating multi-threaded front-end web apps with WebAssembly. This project serves as a simple starter template to get familiar with Yew and its ecosystem.

## Prerequisites

To run this project, you need to have the following installed:

- Rust: [Install Rust](https://www.rust-lang.org/tools/install)
- wasm-pack: [Install wasm-pack](https://rustwasm.github.io/wasm-pack/installer/)
- npm or yarn: [Install Node.js](https://nodejs.org/) (which includes npm) or [Yarn](https://yarnpkg.com/getting-started/install)

## Getting Started

1. **Clone the repository**:
    ```sh
    git clone https://github.com/nerkled/yew-app.git
    cd yew-app
    ```

2. **Build the project**:
    ```sh
    wasm-pack build
    ```

3. **Install dependencies**:
    ```sh
    cd www
    npm install
    ```

4. **Run the development server**:
    ```sh
    npm start
    ```

5. **Open your browser** and navigate to `http://localhost:6969` to see the app in action.

## Project Structure

- **src**: Contains the Rust source code for the Yew app.
- **www**: Contains the frontend files including the entry point for the web app and the configuration for webpack.

## Key Dependencies

- [Yew](https://yew.rs/docs/getting-started/introduction): The framework used for building the web app.
- [wasm-bindgen](https://rustwasm.github.io/wasm-bindgen/): Facilitates high-level interactions between WebAssembly (compiled from Rust) and JavaScript.

## Learning Resources

- [Yew Documentation](https://yew.rs/docs/getting-started/introduction)
- [Rust and WebAssembly Book](https://rustwasm.github.io/docs/book/)

## Contributing

This is just an experimental project. Feel free to fork the repository and play around with the code. If you find something interesting or have suggestions, feel free to open an issue or a pull request.

## License

This project is licensed under the MIT License.
