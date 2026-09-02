# NoBlox App Templates

Public catalog and registry metadata for reusable NoBlox website templates.

NoBlox turns a short business description into a fast, publishable website.
This repository is the discovery layer for those site foundations: it records
template identity, framework, industries, supported capabilities, provenance,
and license-review status.

## Distribution model

The catalog is intentionally lightweight. Installing NoBlox does not download
this repository or every template. The NoBlox CLI reads the catalog, then
downloads only the selected, approved template artifact from a versioned
release or registry endpoint.

Each artifact must be immutable, checksum-addressed, and accompanied by a
completed license review before it is published for reuse. Current entries
are metadata-only drafts while their source and asset redistribution rights
are reviewed. Do not treat `status: draft` entries as downloadable or
production-ready templates.

## Layout

```text
catalog.json
templates/<template-id>/template.json
templates/<template-id>/preview.png
screenshots/<template-id>/homepage.png
```

Desktop previews are indexed in [`screenshots/README.md`](screenshots/README.md).

The full artifact contract will add a versioned release manifest, SHA-256,
preview assets, compatibility data, and license evidence. Generated workspaces,
local paths, caches, credentials, and raw capture evidence do not belong in
this public repository.

## Contributing

Every new template needs:

- stable ID and version;
- provenance and source URL;
- explicit artifact contents;
- license and redistribution evidence;
- framework and compatibility metadata;
- preview and validation evidence;
- a deterministic checksum for the released artifact.

Until those checks pass, keep the catalog entry in `draft` or `restricted`.
