
rustup install 1.60.0

rustup override set 1.60.0

cargo build --release

./openethereum --config ./config.toml
