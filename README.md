```
rustup toolchain install nightly
```

```
sudo apt install avr-libc gcc-avr pkg-config avrdude libudev-dev build-essential
```

```
cargo +stable install ravedude
```

```
cargo install cargo-generate
cargo generate --git https://github.com/Rahix/avr-hal-template.git
```

Give a name to the project that you want to create.
Select the board.
Find the serial usb device's path
```
export RAVEDUDE_PORT=/dev/ttyUSB0
cargo run
```
