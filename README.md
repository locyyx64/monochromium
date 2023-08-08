# ![Logo](chrome/app/theme/chromium/product_logo_64.png) Chromium

Chromium is an open-source browser project that aims to build a safer, faster,
and more stable way for all users to experience the web.

The project's web site is https://www.chromium.org.

To check out the source code locally, don't use `git clone`! Instead,
follow [the instructions on how to get the code](docs/get_the_code.md).

Documentation in the source is rooted in [docs/README.md](docs/README.md).

Learn how to [Get Around the Chromium Source Code Directory Structure
](https://www.chromium.org/developers/how-tos/getting-around-the-chrome-source-code).

For historical reasons, there are some small top level directories. Now the
guidance is that new top level directories are for product (e.g. Chrome,
Android WebView, Ash). Even if these products have multiple executables, the
code should be in subdirectories of the product.

If you found a bug, please file it at https://crbug.com/new.

# For Monochromium

Since Chromium is a huge and very complex system, I first have to understand how it works before I start developing Monochromium. Plus, since I've last coded in C++, I have forgotten a lot of stuff.
Long story short, I won't be active on this repo for quite some months.

## Main Goals with Monochromium

Monochromium is going to be a simplicity-based, and privacy-based open-source browser. The reason why I named it 'Mono'chromium, is because its only main purpose, that sets it apart from Chromium will be its enhanced privacy.
The main "search engine" on it will be SearXNG, with the use of Tor networking. Also, I will probably cut down on the unnecessary features that Chromium has by default.
