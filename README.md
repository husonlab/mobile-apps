# husonlab mobile apps

The public website for the husonlab apps for iPhone and iPad (SplitsTree, PhyloSketch, CatReNet and
PhyloParallelograms), published with GitHub Pages at <https://husonlab.github.io/mobile-apps/>.

It holds the pages that the App Store listings link to: the description and support page of each app, the
privacy policy and the third-party notices. The apps' source code lives in private repositories; the desktop
programs they are built from are open source and linked from the pages.

## Updating

- `index.md` and the app pages (`splitstree.md`, `phylosketch.md`, `catrenet.md`, `phyloparallelograms.md`):
  plain Markdown, rendered with the `jekyll-theme-minimal` theme configured in `_config.yml`.
- `privacy.md`: the privacy policy. Change the effective date when the text changes.
- `licenses.md`: the introduction followed by the contents of `THIRD-PARTY-NOTICES.dat` from the
  `mobile-support` library (`src/main/resources/mobilesupport/about/`), which is also what the apps show in
  their About pane. Regenerate that file whenever the dependencies change and copy it here.
- `assets/icons/`: the app icons at 256 px.
