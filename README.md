# Twemoji

A simple library that provides standard Unicode [emoji](https://en.wikipedia.org/wiki/Emoji) support across all platforms.

**Twemoji v17.0** adheres to the [Unicode 17.0 spec](https://unicode.org/versions/Unicode17.0.0/) and supports the [Emoji 17.0 spec](https://www.unicode.org/reports/tr51/tr51-29.html).

The Twemoji library offers support for all Unicode-defined emoji which are recommended for general interchange (RGI), and in this fork a few that are extra.

## Changes

* Change the Antartica flag emoji [#11](https://github.com/jdecked/twemoji/pull/11)
* Add Quebec (CA-QC) flag [#50](https://github.com/jdecked/twemoji/pull/50)
* two emoji consistency fixes [#74](https://github.com/jdecked/twemoji/pull/74)
* Adding subdivision flags, USA [#99](https://github.com/jdecked/twemoji/pull/99)


## Usage

### Download

I will try to provide a TTF file in the Releases tab made with [WhyNotHugo's script](https://git.sr.ht/~whynothugo/twemoji.ttf/tree/main/item/.build.yml), which I [made into a repo](https://github.com/ez-me/noto-emoji-slim/), for convenience.

I will also provide a custom Magisk module based on my own [Twemoji replacer](https://github.com/Magisk-Modules-Alt-Repo/ttf-twemoji/)

## Tips

### Inline Styles

If you'd like to size the emoji according to the surrounding text, you can add the following CSS to your stylesheet:

```css
img.emoji {
   height: 1em;
   width: 1em;
   margin: 0 .05em 0 .1em;
   vertical-align: -0.1em;
}
```

This will make sure emoji derive their width and height from the `font-size` of the text they're shown with. It also adds just a little bit of space before and after each emoji, and pulls them upwards a little bit for better optical alignment.

### UTF-8 Character Set

To properly support emoji, the document character set must be set to UTF-8. This can be done by including the following meta tag in the document `<head>`

```html
<meta charset="utf-8">
```

<details>

<summary>Stuff from upstream</summary>

## Contributing

The contributing documentation can be found [here](CONTRIBUTING.md).

## Attribution Requirements

As an open source project, attribution is critical from a legal, practical and motivational perspective in our opinion. The graphics are licensed under the CC-BY 4.0 which has a pretty good guide on [best practices for attribution](https://wiki.creativecommons.org/Best_practices_for_attribution).

However, we consider the guide a bit onerous and as a project, will accept a mention in a project README or an 'About' section or footer on a website. In mobile applications, a common place would be in the Settings/About section (for example, see the mobile Twitter application Settings->About->Legal section). We would consider a mention in the HTML/JS source sufficient also.

## Committers and Contributors

* Justine De Caires (ex-Twitter)
* Jason Sofonia (ex-Twitter)
* Bryan Haggerty (ex-Twitter)
* Nathan Downs (ex-Twitter)
* Tom Wuttke (ex-Twitter)
* Andrea Giammarchi (ex-Twitter)
* Joen Asmussen (WordPress)
* Marcus Kazmierczak (WordPress)
* Kevin VQ Dam (ex-Discord)
* Gica Tam (Discord)
* Ben Olson (Discord)

The goal of this project is to simply provide emoji for everyone. We definitely welcome improvements and fixes, but we may not merge every pull request suggested by the community due to the simple nature of the project.

The rules for contributing are available in the [`CONTRIBUTING.md`](CONTRIBUTING.md) file.

Thank you to all of our [contributors](https://github.com/jdecked/twemoji/graphs/contributors).

## License

See the [LICENSE](LICENSE) and [LICENSE-GRAPHICS](LICENSE-GRAPHICS) files for full license texts.

Code licensed under the MIT License: <http://opensource.org/licenses/MIT>

Graphics licensed under CC-BY 4.0: <https://creativecommons.org/licenses/by/4.0/>

</details>
