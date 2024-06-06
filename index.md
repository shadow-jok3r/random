# barf

**barf is an extremely minimal blog generator.**

The entire build script is less than 100 lines of shell.

It could almost be called "suckless", but probably isn't. It was created for those focused on writing, not tinkering.

You can learn more by reading the [official README](https://git.btxx.org/barf/about) and view the generated [Atom feed here](/atom.xml)

**barf** = blogs are really fun

---

### Get setup in 2 minutes

**Install dependencies:**
* For Linux: `rsync`
* For macOS: `brew install coreutils gnu-sed`
* For OpenBSD: `doas pkg_add rsync coreutils gsed cmake gcc`

**Clone and install the lightweight markdown parser, `smu`**
* `git clone https://git.btxx.org/smu`
* `cd smu ; make ; sudo make install`

**Clone `barf`:** 
* `git clone https://git.btxx.org/barf`

1. Open project, change the `domain` variable at the top of the core barf file
2. Run: `make build`
3. Upload the contents of `build` to your server! 
4. Profit?

---

### Articles
