This my website, borrowed from [dmetaxak/dmetaxak.github.io][dm] who borrowed from Ali Alkhatib's [instructions][ali]. The design, code, and content are made available under the [Creative Commons Attribution][cc-by] license.
[dm]:  dmetaxak/dmetaxak.github.io
[ali]: https://github.com/alialkhatib/alialkhatib.github.io
[cc-by]: http://creativecommons.org/licenses/by/3.0/us/

## Analytics setup

To track visitors (views + locations), pick one and put its ID in `_config.yml`:

- **GoatCounter** (free, privacy-friendly, no cookie banner needed): sign up at
  [goatcounter.com](https://www.goatcounter.com), choose a code (e.g. `valentinapy`),
  then set `goatcounter: valentinapy` in `_config.yml`. Dashboard shows views,
  referrers, and visitor countries.
- **Google Analytics 4** (more detail, city-level locations): create a property at
  [analytics.google.com](https://analytics.google.com), copy the `G-XXXXXXXXXX`
  measurement ID, then set `google_analytics: G-XXXXXXXXXX` in `_config.yml`.
