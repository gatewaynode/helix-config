Introduction
---
This is my config for Helix editor, it also contains my theme "Fallout".

Installation
---
1. Install Rust
  - `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`
2. Install Helix Editor from source
  - https://docs.helix-editor.com/master/install.html#build-from-source
3. Install Rust-Analyzer (binary method)
  - https://rust-analyzer.github.io/manual.html#rust-analyzer-language-server-binary
4. Install Python LSP (package manager method)
  - `sudo apt install python3-pylsp`
5. Install ShellCheck (package manager method)
  - `sudo apt install shellcheck`
6. Install Bash-Language-Server (npm method)
  - `npm i -g bash-language-server`
7. Clone this repository into XDG config dir for Helix
  - `cd ~/.config/helix; git clone git@github.com:gatewaynode/helix-config.git; mv helix-config/.git ./; mv helix-config/* ./; rm -rf helix-config`
8. Test that Rust, Python, and Bash LSP's are working
  - `hx --health`
