# Karel Reader

## Fork notes

I love the [Karel
Reader](https://compedu.stanford.edu/karel-reader/docs/python/en/intro.html) but the build
system for this project makes me sweat 😅 and I needed a fun, non-work related project in
my life *so*. Here we are.

### Optimistic Roadmap

- [ ] Decide on a nicer build system
  - [mdBook](https://rust-lang.github.io/mdBook/for_developers/preprocessors.html) is
    nice, plus, I could write a custom preprocessor and use it as an excuse to learn Rust!
  - ...but I'm already comfortable writing plugins for unified/rehype/remark so a
    Node-based static site generator would probably be a better choice
    - (plus, it'd be nice to have Webpack support)
