# maketitle-tl-b

Half of the TeX Live tree that [maketitle](https://github.com/voyager-from-space/maketitle) loads on demand, split in two so each half stays under jsDelivr's 150 MB limit for a GitHub repository. The page reads it through jsDelivr, pinned to the tag `tl1`; the whole tree is also served from [maketitle-texlive](https://github.com/voyager-from-space/maketitle-texlive) on GitHub Pages as the fallback.

This half: the BusyTeX engine (`e/busytex-*.wasm.gz`) and packs `p/80` to `p/ff`.

The layout and licences are described in the maketitle-texlive README. The engine is BusyTeX (AGPL-3.0); TeX Live files keep their own licences (LPPL, GPL, OFL, public domain and others).
