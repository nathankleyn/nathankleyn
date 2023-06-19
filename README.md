### Hi! 👋

I'm Nathan, and I currently work for [Pave](https://paveapp.com/) as the Head of Engineering and Product, writing Ruby by day and functional Rust and Scala by night. [I write for SitePoint about Ruby](https://www.sitepoint.com/author/nkleyn/), and [I'm writing interesting thoughts about all sorts on my blog](https://nathankleyn.com/). You can also find me on [Twitter](https://twitter.com/nathankleyn) and of course here on GitHub. If you want to email me the old fashioned way, you can get in touch with me at mail/at/nathankleyn.com.

```rust
static NAME: &'static str = "Nathan";
static COMPANY: &'static str = "Portify";
static MY_WEBSITE_AND_BLOG: &'static str = "https://nathankleyn.com/";
static COMPANY_WEBSITE: &'static str = "https://paveapp.com/";
static TWITTER: &'static str = "https://twitter.com/nathankleyn";
static EMAIL: &'static str = "mail/at/nathankleyn.com";
static SITEPOINT_PROFILE: &'static str = "https://www.sitepoint.com/author/nkleyn/";

fn main() {
    println!("{}", github_readme());
}

fn github_readme() -> String {
    format!("I'm {}, and I currently work for [{}]({}) as the Head of Engineering and Product, \
             writing Ruby by day and functional Rust and Scala by night. \
             [I write for SitePoint about Ruby]({}), and \
             [I'm writing interesting thoughts about all sorts on my blog]({}). \
             You can also find me on [Twitter]({}) and of course here on GitHub. \
             If you want to email me the old fashioned way, you can get in touch with me at {}.",
             NAME, COMPANY, COMPANY_WEBSITE, SITEPOINT_PROFILE, MY_WEBSITE_AND_BLOG, TWITTER, EMAIL)
}
```

https://play.rust-lang.org/?version=stable&mode=debug&edition=2018&gist=317f0bdf9e6e0015c86a8dea948a73b4
