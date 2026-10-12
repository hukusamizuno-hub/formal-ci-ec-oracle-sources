# Formal-CI EC oracle: corresponding sources and notices

Source publication is in progress. The five release assets are immutable, approved preparation snapshots; their README/status text records the preparation-time gate. Release notes will record anonymous-download verification when complete. GHCR image publication remains gated separately.

## Exact container

- Target: `ghcr.io/hukusamizuno-hub/formal-ci-ec-oracle:amd64-h3-08b3cdb74e2a-71acd1210842484c94b7c03c2e3dfaaf`
- Platform: `linux/amd64`
- Local Docker manifest identity: `sha256:2d3fe158916e194764d50588fab202bc344336c365ad44bc6d2457b574263cee`
- Config SHA-256: `485b8c3b1d52b194581ba1975d21130ea9a217b8bc430deca8f448ba2327917a`
- Registry digest: pending registry readback; the local identity above is not a registry confirmation.
- This is a generic runtime. No EC application or oracle harness source is included.

## Source distribution

Release: https://github.com/hukusamizuno-hub/formal-ci-ec-oracle-sources/releases/tag/oracle-amd64-71acd121

Download all three companion archives and SHA256SUMS without login or payment:

1. `debian-corresponding-sources.tar`: 85 exact Debian source package versions covering 123 binary package/version pairs across all distributed layers, including both Perl revisions. Every declared original component, Debian packaging/patches, build/install rules and source descriptor is included.
2. `python-corresponding-sources.tar`: CPython 3.12.15, pip 25.0.1 and 18 exact vendored component source versions. pip's exact tagged source additionally supplies its vendoring tools and six patch files; all 261 vendored Python files match the exact pip sdist byte-for-byte.
3. `licenses-and-evidence.tar.gz`: unchanged image notices (135 layer documents), supplemental upstream notices, full notice compilation, source and binary mappings, Dockerfile, SHA-bound public-data classification and distribution instructions.

Verify SHA256SUMS before unpacking. Source descriptors name every required component and its hash. For Debian source reconstruction use the complete matching .dsc and component files with standard `dpkg-source -x`; version-specific `debian/rules`, patches and build dependencies remain inside each source package. This is source delivery, not a claim of a byte-identical rebuild test. Upstream language archive build/install files remain unchanged. No source version was replaced with a newer version.

## License obligations and chosen fulfillment method

- GPL programs (including Git, bash, coreutils and dpkg) and LGPL libraries: preserve their individual copyright notices, license text, disclaimers and exact source including distributor patches and build/install scripts. Supply actual source downloads with equivalent access beside binary download directions. Do not rely solely on a third party's rolling mirror, a bare license label, an expired version URL, or an unfulfilled written offer. This plan supplies source directly and does not use GPL section 3(b)'s written-offer alternative.
- LGPL: preserve modification/reverse-engineering rights for debugging modifications and source/relinking rights under each applicable version. This generic container imposes no restrictive EULA or signature requirement; library components are dynamically linked. GCC runtime exceptions and other package-specific exceptions remain in the original notices; no blanket license is imposed on the collection.
- CPython PSF and pip/vendor MIT/BSD/Apache/other terms: retain copyrights, license texts, attribution and applicable NOTICE material. Exact pip modified vendored sources and upstream patch tooling are supplied. certifi's MPL-2.0 source is included; its source availability and notice conditions are retained. The common/image license documents include MPL-2.0 text through the ca-certificates copyright file. Documentation/source files retain their own terms, including GFDL and Artistic where applicable.
- Every component is offered under its original applicable terms. No warranty is added. Source and notice bundles do not relicense the components.
- Source downloads and notices must stay available for as long as this binary distribution relies on them; if access fails, stop distribution until repaired. Retain the exact assets instead of redirecting to latest versions.

## Publication gate

The secret scanner's original failed report is unchanged. All 22 hits are accounted for by 11 public data locations: ten GnuTLS cryptographic self-test vectors and one libssh2 PEM format constant. Classification is tied to this exact manifest, exact full-file hashes, public Debian binary equality and exact source C-string fingerprints. It is not a pattern exemption for other files or images.

License preparation is complete locally. Source-delivery verification is in progress until this release offers binary retrieval directions together with anonymous source/notices asset downloads and their SHA-256 hashes have been read back. No GHCR push is allowed before source delivery has been verified. If the first approved push creates a new private package, set and verify its adjacent source/notices directions before making it public; if it is already public, stop until equivalent adjacent directions are established. Public package description must include this exact source release and notices directions together with the image instructions. Once public, verify package visibility and registry digest independently before H4/W4 pinning.

## Primary references

- GPL-2 section 3, distributed with Git: https://raw.githubusercontent.com/git/git/v2.39.5/COPYING
- Debian redistribution: https://www.debian.org/doc/manuals/debian-faq/redistributing.en.html
- MPL-2.0 section 3: https://www.mozilla.org/en-US/MPL/2.0/
- Exact pip vendoring sources: included upstream `pip-25.0.1/src/pip/_vendor/README.rst` and `tools/vendoring/patches/`.
- GitHub release asset limits: https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases

Download provenance is official Debian/Python/PyPI/GitHub HTTPS plus recorded SHA-256 checks. Debian Release/OpenPGP signatures were not independently verified in this preparation; no claim of such verification is made.
