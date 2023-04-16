### Java

**File:** java-format.xml <br>
**File Location:** Anywhere (Specifically `~/.format` for vscode settings) <br>
**Options:** [Eclipse Formatter Constants](https://help.eclipse.org/latest/index.jsp?topic=%2Forg.eclipse.jdt.doc.isv%2Freference%2Fapi%2Forg%2Feclipse%2Fjdt%2Fcore%2Fformatter%2Fpackage-summary.html) [**Archived**](https://web.archive.org/web/20230416172329/https://help.eclipse.org/latest/index.jsp?topic=%2Forg.eclipse.jdt.doc.isv%2Freference%2Fapi%2Forg%2Feclipse%2Fjdt%2Fcore%2Fformatter%2Fpackage-summary.html)

### C / C++

**File:** .clang-format <br>
**File Location:** Anywhere (Specifically `~/.format` for vscode settings) <br>
**Options:** [Clang Format Style Options](https://clang.llvm.org/docs/ClangFormatStyleOptions.html) [**Archived**](https://web.archive.org/web/20230401042727/https://clang.llvm.org/docs/ClangFormatStyleOptions.html)

### Rust

**File:** .rustfmt.toml <br>
**File Location:** In either the home directory `~` or the rustfmt config folder `~/.config/rustfmt`
**Options:** [Rustfmt Configuration](https://rust-lang.github.io/rustfmt/?version=v1.5.1) [**Archived**](https://web.archive.org/web/20230416173244/https://rust-lang.github.io/rustfmt/)

### VSCode

**File:** settings.json <br>
**File Location:** Place into VSCode settings location, file paths may need to be updated where required

**File:** extensions.sh <br>
**Prerequisites:** `chmod u+x extensions.sh` to allow the current user to execute the file as a shell script <br>
**Use:** To install all the extensions listed in the file run it using `./extensions.sh`
**Creation:** To generate this file from the current VSCode run `code --list-extensions | xargs -L 1 echo code --install-extension > extensions.sh`, a file called extensions.sh will be produced in the currect directory