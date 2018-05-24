```bash
cd rust
cargo build --release
cp target/release/libembed.so ../node.native
cd ..
zip -r embed.zip node/*
```
