# meta-lts-mixin scarthgap/nodejs

"Mixin" layer for adding current nodejs into the Yocto Project LTS.

At the time Scarthgap was released in April 2024 it included nodejs 20.12.2,
and officially Scarthgap supports only that. This thin special-purpose
mixin layer is meant to provide a current nodejs for Scarthgap
by extending or backporting the appropriate recipes from the master branch of
openembedded-core.

Maintainers:
- Ariel D'Alessandro <ariel.dalessandro AT collabora DOT com>
