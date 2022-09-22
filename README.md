This is a rust template that can be used to quickstart any rust project.
Things are set here based on personal preference of the [author](https://github.com/rctrj)

Integrations:
1. Cargo
2. Branch Name Validation
3. Commit Title Validation using [commitlint](https://github.com/conventional-changelog/commitlint)
4. Rust Fmt settings

Todos:
* [ ] CI
* [ ] CD
* [ ] Commit Template
* [ ] Run RustFMT pre-commit

---
## Initial Setup ##
This project requires you to run a few commands before you can work in this.
Please note that skipping this might result in your commits and branches getting rejected upon push.

The following steps require that you have npm and git install in your system
Steps:
1. Goto: tools/git
2. Give permission to `init_setup.sh` using `chmod +x init_setup.sh`
3. Run `init_setup.sh`

This should create a `.husky` folder which is used for commit validation