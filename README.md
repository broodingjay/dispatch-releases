# writer-releases

Build artefacts and the Sparkle update feed for **Writer**, a markdown app for macOS.

This repository is public on purpose and holds no source code. An installed copy of
Writer reads `appcast.xml` from here with no credentials, which is the only reason
it cannot live alongside the private source repo. It mirrors the arrangement Feeds
already uses.

`appcast.xml` is the permanent address every shipped build polls. It cannot be
moved without stranding every copy already sold.
