# kagi-gruv-css
Dark Gruvbox CSS style for the paid Kagi search engine.

## How to Install

1. Open Kagi and go to `Settings > Appearance`.
2. Toggle theme to the `Dark` theme if it isn't already selected.
3. Go to `Custom CSS` section.
4. Toggle `Enable CSS`.
5. Paste or import(?) (TODO check if this works) [kagi.css](/) 
6. Click `Save Changes`.

> [!NOTE]
> This style is incomplete and assumes you only have the Wikipedia search widget enabled. Also I've only tested it on Firefox 146.0.1 and mobile Chromium (GrapheneOS Vanadium). 

## Tweaks
### Change Font
I use Atkinson Hyperlegible Next because its easier for me to read if I'm not wearing my glasses. Change `--font-main` to any font you'd like. 
### Re-enable AI button in search
Remove `visbility: hidden;` from `._0_quick_answer_trigger_btn`.

## Resources
- [Official Kagi Help Page](https://help.kagi.com/kagi/features/custom-css.html)
- Another [Gruvbox theme by Auphone](https://auphone.net/posts/kagi-gruvbox-dark-theme-css/)
- [Gruvbox](https://github.com/morhetz/gruvbox)
- [MDN CSS Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS)
