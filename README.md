#image-base64-rs

<p align="left">
    <a href="https://crates.io/crates/image-base64">
        <img src="https://img.shields.io/crates/v/image-base64.svg"
             alt="crates">
    </a>
    <a href="https://travis-ci.org/katsumeshi/image-base64-rs">
        <img src="https://travis-ci.org/katsumeshi/image-base64-rs.svg?branch=master"
             alt="travis">
    </a>
    
    
</p>
Convert image/audio to base64, and vise versa

## Code Example

```
extern crate ts_base64;

fn main() {
  let base64 = "base64 String";
  let image = ts_base64::from_base64(base64);
  
  let image_path = "local image file path"
  let base64 = ts_base64::to_base64(image_path); 
}
```

## Installation

Add the dependency to your `Cargo.toml`:

```toml
[dependencies]
image-base64 = "0.1"
```

## Tool
https://en.wikipedia.org/wiki/List_of_file_signatures

## License

MIT
