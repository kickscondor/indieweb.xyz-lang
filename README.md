# Indieweb.xyz Translations

[Indieweb.xyz](https://indieweb.xyz/) is a syndication service organized into
*subs*, similar to Reddit. All interaction with the site, such as linking and
upvoting, is performed by Webmention. Discussion happens on blog posts
themselves, as per Indieweb convention.

> :wave: Welcome to the translation project for Indieweb.xyz. This repo houses
> all of the text used throughout the site, to allow anyone to translate the
> text to a desired language.

To add a new language, please send a pull request containing your translation
changes. The following steps must be taken for this translation to be accepted.

* **A language code must be created.** For English, the *en* code is used; for
  German, the *de* code. The code is created by adding a
  [YAML](https://www.yaml.org/) document named *code*.yml in the root directory
  of this repository. (The *lang/en.yml* file should be used as a basis.)

* **The text of the file must be translated, but not the 'keys'.** Keys, such
  as `title`, `months-ago` or `howto-menu` should stay in English. The file
  itself must be encoded as UTF-8.

Some entries have special syntax.

* In the *Time Display* section of the file, certain entries must contain an
  `X`. This X will be replaced with the number of months or days that the text
  will represent.

* The `{{lang}}` placeholder is replaced on the site with the language code
  created earlier.

## URLs for Each Language

The language code is also used in the URLs for Indieweb.xyz pages.

The subs themselves will appear at: `https://indieweb.xyz/{{lang}}/sub-name`.

Other instructional and feed pages will have the language code as a suffix:
`https://indieweb.xyz/howto/en`, for example.
