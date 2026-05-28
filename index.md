# barf

**barf is an extremely minimal blog generator.**

The entire build script is >170 lines of shell.

It could almost be called "suckless", but probably isn't. It was created for those focused on writing, not tinkering.

You can learn more by reading the [official README](https://git.sr.ht/~bt/barf).

**barf** = blogs are really fun

---

### Get setup in 2 minutes

**Install dependencies:**

For Linux (Alpine example):

    sudo apk add rsync coreutils cmake

For macOS:

    brew install rsync coreutils gnu-sed cmake multimarkdown

For OpenBSD:

    doas pkg_add coreutils gsed cmake gcc

**Build MultiMarkdown (Linux)**

```
git clone https://github.com/fletcher/MultiMarkdown-6.git
cd MultiMarkdown-6
sudo cmake . -DCMAKE_BUILD_TYPE=Release
sudo make
sudo make install
```

**Clone barf:** 

    git clone https://git.sr.ht/~bt/barf

1. Open project, change the `domain` variable at the top of the core barf file
2. Run: `make build`
3. Upload the contents of `build` to your server! 
4. Profit?

---

### Articles
