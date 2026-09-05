# cbc-social-assets

Rendered Instagram cards for **@crossborder.cosmetics**, published here so they
have a public HTTPS URL. Nothing else lives in this repository.

All files are **1080 × 1080** JPEG — square, which is the ratio every CBC post
uses. Post them in slide order; Instagram re-serves a carousel starting from
card 2, so the order carries meaning.

| Folder | Post | Slides |
| --- | --- | --- |
| `post-01/` | Six questions to ask before you fly to Thailand for surgery | 8 |
| `post-02/` | Two procedures, one price — the offer that is prohibited | 1 |
| `post-03/` | Recovery after breast augmentation, week by week | 8 |

## Getting the files

**Laptop** — green **Code** button → **Download ZIP** takes the lot in one go.

**Phone** — open a slide, long-press, save. That is eight taps per carousel, so
the ZIP on a laptop and then AirDrop or Drive to the phone is usually less work.

## These are outputs, not sources

Every image here is generated from an HTML renderer in the CBC vault
(`tools/brand/`), which reads one locked type scale. Edit the renderer and
re-export; do not retouch a JPEG in this repository, because the next export
will overwrite it.
