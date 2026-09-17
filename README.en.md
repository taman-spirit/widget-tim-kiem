# Search box

A search box that opens results on Nhat Nguyet in a new tab.

*[Đọc bản tiếng Việt](README.md)*

**See it running:** https://nhatnguyet.org/widget/tim-kiem

## Paste these two lines

```html
<div data-widget="tim-kiem"></div>
<script async src="https://nhatnguyet.org/embed/w.js"></script>
```

No account, no API key, nothing to pay.

## What it gives your page

A compact search box that sends your readers straight into the Nhat Nguyet knowledge base. Suggestions appear as they type, and there is a voice button as well. Results open in a new tab, so nobody gets pulled away from your page.

## Worth knowing before you embed

- The smallest one here: a single line, sized for the gap at the top or bottom of a sidebar.
- Results open in a new tab, so your reader is not pulled away from your page.
- Suits sites writing about feng shui, astrology or the lunar calendar that have no lookup tool of their own.

## The steps

1. Paste the snippet into your sidebar, just above or below your own search box.
2. The reader types a keyword and presses Enter.
3. They can also tap the microphone button to search by voice.

## Where to paste it

**WordPress.** Add a *Custom HTML* block to the post, or a *Text* widget in
the sidebar, and paste both lines there. Do not paste into the ordinary
editor: it will show the code as text instead of running it.

**Wix, Squarespace, Shopify.** Use the *Embed HTML* / *Custom HTML* block.

**Hand-written sites.** Paste it straight where you want the widget. If you
embed several widgets, the `<script>` line only needs to appear once on the
page.

**A note on width.** The widget fits the width of wherever you put it.

## Make it match your page

| Attribute | Values | Meaning |
|---|---|---|
| `data-widget` | `tim-kiem` | Required |
| `data-theme` | light or dark | Defaults to light |
| `data-accent` | #b3341f | Accent colour as a 6-digit hex value, to match your own branding |
| `data-lang` | vi or en | Defaults to vi |

With every attribute this widget accepts, it looks like this:

```html
<div data-widget="tim-kiem" data-theme="dark" data-accent="#1f6f5c" data-lang="en"></div>
<script async src="https://nhatnguyet.org/embed/w.js"></script>
```

Want to see it for yourself before it goes near your real page? Open
[`vi-du/index.html`](vi-du/index.html) in a browser, nothing to install.

## A few things we ask

- Free for personal and business websites, with no display limit.
- Keep the attribution line at the foot of the widget. That is what you give
  in return for free use.
- Do not embed on gambling, adult, fraudulent sites or anything unlawful
  under Vietnamese law.
- The content is folk knowledge and cultural convention, offered as
  reference, not as health, financial or legal advice.

Full text: [`TERMS.md`](TERMS.md) · [https://nhatnguyet.org/widget/dieu-khoan](https://nhatnguyet.org/widget/dieu-khoan)

## Who we are

Nhat Nguyet (https://nhatnguyet.org) is a Vietnamese reference site for calendrical and
cultural knowledge: the lunar calendar computed for Vietnam's own time zone,
the sexagenary cycle, solar terms, auspicious hours, astrology, feng shui,
and a glossary of terms.

There is one thing we try hard to keep clear, even inside a 300px frame:
which parts are computed, and which are folk convention.

Lunar dates, sexagenary names and solar terms are **computed**. Run the same
calculation and you get the same answer, and we publish the underlying
datasets under CC BY 4.0 so you can check for yourself.

Auspicious hours, Bat Trach directions and Lo Ban rule bands are **cultural
convention**. There are real lookup tables behind them, but they are not
measurements. The widget tells you what the table says; how much weight to
give it is yours to decide.

Where the schools disagree, we say so, rather than quietly picking a side and
presenting it as the only reading.

Open data: [GitHub](https://github.com/taman-spirit/du-lieu-am-lich) ·
[Hugging Face](https://huggingface.co/datasets/nhatnguyet)

## Something not right?

Open an issue in this repository. We do read them.

The whole widget library: [https://nhatnguyet.org/widget](https://nhatnguyet.org/widget)
