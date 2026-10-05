<!-- tyhp-readme:start -->
# tyhpdef/squizlabs-php_codesniffer

Tyhp type definitions for `squizlabs/php_codesniffer` `3.13.6`.

```bash
composer require --dev tyhpdef/squizlabs-php_codesniffer:3.13.6
```

This is a metapackage. Composer also installs `tyhpdef/squizlabs-php_codesniffer-impl` (type files).
Require **this** name, not `tyhpdef/squizlabs-php_codesniffer-impl`.

See https://tyhplang.com.

## Maintain `squizlabs/php_codesniffer`? Ship the types yourself

If you are a Packagist maintainer of `squizlabs/php_codesniffer`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/squizlabs-php_codesniffer-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `squizlabs/php_codesniffer` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/squizlabs-php_codesniffer": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `squizlabs/php_codesniffer` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `squizlabs/php_codesniffer` with a real constraint,
   `"replace": { "tyhpdef/squizlabs-php_codesniffer": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `squizlabs/php_codesniffer` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/squizlabs-php_codesniffer` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
