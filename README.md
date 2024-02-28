# LC-3
required links: https://www.jmeiners.com/lc3-vm/

[lc3-vm-isa.pdf](https://www.jmeiners.com/lc3-vm/supplies/lc3-isa.pdf)

https://succinctlabs.github.io/sp1/getting-started/install.html
1. rust
2. openssl
3. sp1

then clone this repo: https://github.com/esciiee/lc3-sp1-pv.git
after cloning,
1. cd ./program
2. cargo prove build
3. ls elf # to check the elf file
4. cd ../script
5. cargo run


for troubleshooting for cargo :
1. creates a new directory in lc3-sp1-pv called .vscode, and a file in it called settings.json

   {
    "rust-analyzer.linkedProjects": [
        "./script/Cargo.toml",
        "./program/Cargo.toml"
    ]
}
  thats it till now,
will add some instructions of my choice and prove them.
