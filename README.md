# Goma

This is an example setup of Goma server being coupled with third party RBE backend.

# Contents

Besides some utility code this repository contains two git submodules: [server](https://github.com/operasoftware/goma-server) and [backend](https://github.com/operasoftware/goma-backend). [Server](https://github.com/operasoftware/goma-server) is a fork of [Google's Goma server code](https://chromium.googlesource.com/infra/goma/server/) that was patched for seamless integration with third party RBE backends. Backend is a fork of [BuildGrid](https://gitlab.com/BuildGrid/buildgrid) that was tweaked for proper handling of RBE requests coming from Goma proxy.
