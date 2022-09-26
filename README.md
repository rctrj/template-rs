This is a rust template that can be used to quickstart any rust project.
Things are set here based on personal preference of the [author](https://github.com/rctrj)

Integrations:
1. Cargo
2. Branch Name Validation
3. Commit Title Validation using [commitlint](https://github.com/conventional-changelog/commitlint)
4. Rust Fmt settings
5. CI setup for testing before PR merge
6. Commit Template
7. Run RustFMT pre-commit

Todos:
* [ ] CD

---
## Initial Setup ##
This project requires you to run a few commands before you can work in this.
Please note that skipping this might result in your commits and branches getting rejected upon push.

The following steps require that you have brew install in your system
Steps:
1. Goto: tools/git 
2. Run `init_setup.sh`