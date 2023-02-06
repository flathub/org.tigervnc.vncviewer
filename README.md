# TigerVNC Viewer

Flatpak build of [TigerVNC](https://tigervnc.org/).

## Flatpak release checklist

### Updating TigerVNC

1.  Checkout the `beta` branch.
2.  Update git tags and commits in `org.tigervnc.vncviewer.yml`.
3.  Add `<release/>` tag to `metainfo.patch`. Add `type="development"` for pre-releases.

### Releasing to Flathub

1.  Push beta branch to Github.
2.  Create merge request against [Flathub repo][flathub-repo] `beta` branch.
3.  Test builds from [Flathub beta store][flathub-beta].
4.  Merge `beta` branch into `master` branch.
5.  Push master branch to Github.
6.  Create merge request against [Flathub repo][flathub-repo] `master` branch.

[flathub-repo]: https://github.com/flathub/org.tigervnc.vncviewer
[flathub-beta]: https://beta.flathub.org/apps/details/org.tigervnc.vncviewer
