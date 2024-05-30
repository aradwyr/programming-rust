```
cargo build --release
time target/release/mandelbrot mandel.png 4000x3000 -1.20,0.35 -1,0.20
```
Will see some output similar to: 
`target/release/mandelbrot mandel.png 4000x3000 -1.20,0.35 -1,0.20  4.23s user 0.02s system 539% cpu 0.787 total`