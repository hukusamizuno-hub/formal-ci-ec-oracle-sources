# Formal-CI EC oracle: corresponding sources and notices

Source publication and anonymous download verification completed on 2026-10-12. All five Release assets matched their approved byte sizes and SHA-256 hashes. GHCR image publication is still pending.

## Exact runtime

- Platform: `linux/amd64`
- Target: `ghcr.io/hukusamizuno-hub/formal-ci-ec-oracle:amd64-h3-08b3cdb74e2a-71acd1210842484c94b7c03c2e3dfaaf`
- Local manifest identity: `sha256:2d3fe158916e194764d50588fab202bc344336c365ad44bc6d2457b574263cee`
- Config SHA-256: `485b8c3b1d52b194581ba1975d21130ea9a217b8bc430deca8f448ba2327917a`
- Registry digest: pending independent registry readback.
- Generic runtime only; no EC application or oracle harness source, business data or owner authentication data.

## Download sources and notices

[Release oracle-amd64-71acd121](https://github.com/hukusamizuno-hub/formal-ci-ec-oracle-sources/releases/tag/oracle-amd64-71acd121) provides these five files without login or payment:

1. `debian-corresponding-sources.tar`: 85 exact Debian source versions covering 123 binary package/version pairs across all distributed layers, including both Perl revisions. Original components, distributor patches, packaging and build/install scripts are included.
2. `python-corresponding-sources.tar`: CPython 3.12.15, pip 25.0.1, 18 exact vendor source versions, and matching pip vendoring tools and six patches. All 261 vendored Python files match the exact pip sdist.
3. `licenses-and-evidence.tar.gz`: original notices, supplemental vendor notices, corresponding-source indices, generic reviewed Dockerfile and hash-bound scan adjudication.
4. `SHA256SUMS`: checksums for the three archives.
5. `README.md`: unchanged approved preparation snapshot. Its pending-status text is historical; this repository README and current release notes record completion.

Check every file against [ASSETS_5_MANIFEST.json](ASSETS_5_MANIFEST.json). The release notes repeat all five hashes and byte sizes. [SOURCE_INDEX.debian.json](SOURCE_INDEX.debian.json) and [SOURCE_INDEX.language.json](SOURCE_INDEX.language.json) map exact versions to source components and hashes. No large source archive is stored in Git history; GitHub generated source-code ZIP/tar links contain documentation only.

## Licenses and publication gates

See [LICENSES.md](LICENSES.md) for GPL/LGPL corresponding-source, modification and relinking rights, PSF/MIT/BSD/Apache/MPL notice requirements and component-specific exceptions. Full original terms and attribution are retained in the notice archive and exact upstream sources. Source descriptors and packaging/build files remain included; this is source delivery, not a byte-identical rebuild claim. Keep these exact sources and notices available while distributing the corresponding container.

All 22 original secret-pattern hits were resolved as 11 exact public-data locations: ten GnuTLS cryptographic self-test vectors and one libssh2 PEM format constant, scanned in both complete layer bytes and file content. Exact image/file hashes, official binary equality and source fingerprints are recorded in the notice archive. The original failed report was not changed and no broad scan exemption was added.

The source-supply prerequisite is satisfied by the verified public assets and equivalent source access beside container retrieval directions in the release notes. Before making GHCR public, its package page must visibly link this exact release and notices. Package visibility and registry digest require independent readback before H4/W4 pinning.

Download provenance is official Debian/Python/PyPI/GitHub HTTPS plus SHA-256 checks; independent Debian Release/OpenPGP verification was not performed or claimed.
