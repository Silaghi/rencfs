## How to contribute

1. Fork the repo
2. [Setup](https://github.com/radumarias/rencfs?tab=readme-ov-file#locally) dev env localy, replace url repo with your fork url
3. Become familiar with the [docs](https://github.com/radumarias/rencfs) and [lib docs](https://docs.rs/rencfs/latest/rencfs), then become familiar with the code and running tests and examples
4. **Ask the owner of the project to add your GitHub username to the project** 
5. Make sure there is an open issue or a task in the [project](https://github.com/users/radumarias/projects/1) that you'll be working on. You can see [good for first issues](https://github.com/radumarias/rencfs/issues?q=is%3Aopen+is%3Aissue+label%3Afirst-timers-only+label%3A%22good+first+issue%22)
6. **Assign the issues you are working to you and move them to the corresponding status column as you are working on them. If the taks is not an issue yet, convert it to issue first**
7. Make the changes in your fork
8. If you add new `.rs` files in `examples` member add all these [lines](https://github.com/radumarias/rencfs/blob/main/src/lib.rs#L1-L16) as first ones
9. If you add new packages to the workspace add all these [lines](https://github.com/radumarias/rencfs/blob/main/src/lib.rs#L1-L16) to it's `lib.rs`
   and to any `bin` files (
   like `main.rs` or other files declared as `[[bin]]`)
10. Add tests for your changes, if applicable
11. `cargo fmt --all`, you can configure your **IDE** to do this on
   save, [RustRover](https://www.jetbrains.com/help/rust/rustfmt.html)
   and [VSCode](https://code.visualstudio.com/docs/languages/rust#_formatting)
12. `./check-before-push.sh` or `cmd /c check-before-push.bat` and fix any errors
13. Create a **PR** back to **main** repo to the `main` branch
14. Monitor the checks (GitHub actions run)
15. Respond to any comments
16. In the end, ideally, it will be merged to `main`