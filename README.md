<p align="center">
  <img src="assets/syrox-pkgs.png" width="300" alt="Syrox Packages mascot: a penguin in a box on a conveyor belt" />
</p>

<h1 align="center">Syrox Packages</h1>

<p align="center">The package catalog for <a href="https://github.com/ryro-hq/syrox">Syrox</a>.</p>

This repository contains Syrox package recipes and their pinned sources. The
catalog's `main.srx` exports packages, acquisitions, builds and an application;
`Syrox.lock` pins the catalog inputs. The Syrox standard library is bundled with
the [Syrox engine](https://github.com/ryro-hq/syrox), not duplicated here.

The current catalog includes GNU Hello, glibc and a local bootstrap input.
To check or plan it, use a compatible Syrox revision with the corresponding
standard-library digest in `Syrox.lock`. The lock on `main` predates recent
changes to the engine's bundled standard library.

The [declarative catalog PR](https://github.com/ryro-hq/syrox-pkgs/pull/1)
introduces lazy typed package sets. Its recipe changes and lockfile are under
review; use that branch when testing the new catalog format.

Licensed under the [Apache License 2.0](LICENSE).
