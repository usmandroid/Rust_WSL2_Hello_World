### Debugging Rust with CodeLLDB in VS Code on WSL2 Ubuntu
Build project using:

* Create build using `cargo build`
* tip: `--debug` is the default for `cargo build`; instead `--release` is supported
* Create release build using `cargo build --release`

Check out `.vscode` folder for `launch.json` and `tasks.json` files and update accordingly to start debugging with CodeLLDB on Windows WSL2 Linux/Ubuntu 

Start debugging by running `F5` in your source file by adding breakpoint


---
### Thanks!
Special thanks to [@GameDevGraphics](https://github.com/GameDevGraphics/RustDebugging/blob/master/src/main.rs) for showing this example, also check-out his youtube video here: [How to debug Rust like a PRO](https://www.youtube.com/watch?v=ebNMJ5rKRLU)

---