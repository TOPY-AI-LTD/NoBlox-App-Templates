<div align="center">
  <a href="https://noblox.app/"><img src="assets/noblox-logo.png" alt="NoBlox" width="180" /></a>
  <h1>NoBlox App Templates</h1>
  <p><strong>Fast, focused foundations for sites built to get found.</strong></p>
  <p>Reusable homepage templates and visual directions for NoBlox-powered websites.</p>
  <p>
    <a href="https://noblox.app/">NoBlox</a> ·
    <a href="catalog.json">Template catalog</a> ·
    <a href="screenshots/">Preview gallery</a>
  </p>
</div>

---

## At a glance

| | |
|---|---|
| **13** | Template directions |
| **3** | Preview sizes — desktop, tablet, mobile |
| **Astro-ready** | Designed for fast, content-friendly sites |
| **Registry-first** | Lightweight discovery with on-demand artifacts |

## What this is

NoBlox turns a short business description into a fast, publishable website.
This repository is the public discovery layer for reusable site foundations:
it records template identity, visual direction, industry fit, supported
capabilities, provenance, and license-review status.

The templates are designed to work with NoBlox's handoff to AI CMO, helping a
published site become easier to understand, index, and cite in search and AI
answers.

## Current template previews

These previews are rendered from each template's `homepage.html` at a fixed
1440×900 desktop viewport. Click any image to open the full-size preview.

<table>
  <tr>
    <td width="50%" valign="top"><a href="screenshots/atma-wellness-15-001/desktop.png"><img src="screenshots/atma-wellness-15-001/desktop.png" alt="Atma Wellness 15 001 desktop preview" /></a><h3>Atma Wellness 15 001</h3><p>Luxury wellness · editorial · restorative</p></td>
    <td width="50%" valign="top"><a href="screenshots/beauty-studio-20-001/desktop.png"><img src="screenshots/beauty-studio-20-001/desktop.png" alt="Beauty Studio 20 001 desktop preview" /></a><h3>Beauty Studio 20 001</h3><p>Beauty studio · warm · conversion-focused</p></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><a href="screenshots/gold-pearl-resort-oyugis-k-001/desktop.png"><img src="screenshots/gold-pearl-resort-oyugis-k-001/desktop.png" alt="Gold Pearl Resort Oyugis K 001 desktop preview" /></a><h3>Gold Pearl Resort Oyugis K 001</h3><p>Resort · premium · hospitality</p></td>
    <td width="50%" valign="top"><a href="screenshots/korean-head-spa-52-001/desktop.png"><img src="screenshots/korean-head-spa-52-001/desktop.png" alt="Korean Head Spa 52 001 desktop preview" /></a><h3>Korean Head Spa 52 001</h3><p>Head spa · calm · treatment-led</p></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><a href="screenshots/lillies-spa-beauty-salon-001/desktop.png"><img src="screenshots/lillies-spa-beauty-salon-001/desktop.png" alt="Lillies Spa Beauty Salon 001 desktop preview" /></a><h3>Lillies Spa Beauty Salon 001</h3><p>Beauty salon · luxury · British editorial</p></td>
    <td width="50%" valign="top"><a href="screenshots/luxury-medspa-27-001/desktop.png"><img src="screenshots/luxury-medspa-27-001/desktop.png" alt="Luxury Medspa 27 001 desktop preview" /></a><h3>Luxury Medspa 27 001</h3><p>Medical spa · clinical · premium</p></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><a href="screenshots/medical-spa-landing-001/desktop.png"><img src="screenshots/medical-spa-landing-001/desktop.png" alt="Medical Spa Landing 001 desktop preview" /></a><h3>Medical Spa Landing 001</h3><p>Aesthetics · wellness · consultation-led</p></td>
    <td width="50%" valign="top"><a href="screenshots/reflexolog-spa-7-001/desktop.png"><img src="screenshots/reflexolog-spa-7-001/desktop.png" alt="Reflexolog Spa 7 001 desktop preview" /></a><h3>Reflexolog Spa 7 001</h3><p>Reflexology · natural · grounded</p></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><a href="screenshots/spa-wellness-1227-001/desktop.png"><img src="screenshots/spa-wellness-1227-001/desktop.png" alt="Spa Wellness 1227 001 desktop preview" /></a><h3>Spa Wellness 1227 001</h3><p>Spa · modern · understated</p></td>
    <td width="50%" valign="top"><a href="screenshots/stillpoint2-001/desktop.png"><img src="screenshots/stillpoint2-001/desktop.png" alt="Stillpoint 2 001 desktop preview" /></a><h3>Stillpoint 2 001</h3><p>Wellness · quiet luxury · immersive</p></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><a href="screenshots/thai-massage-49-001/desktop.png"><img src="screenshots/thai-massage-49-001/desktop.png" alt="Thai Massage 49 001 desktop preview" /></a><h3>Thai Massage 49 001</h3><p>Massage · tactile · warm</p></td>
    <td width="50%" valign="top"><a href="screenshots/wellness-booking-72-001/desktop.png"><img src="screenshots/wellness-booking-72-001/desktop.png" alt="Wellness Booking 72 001 desktop preview" /></a><h3>Wellness Booking 72 001</h3><p>Booking-led · approachable · service-first</p></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><a href="screenshots/wellness-float-11-001/desktop.png"><img src="screenshots/wellness-float-11-001/desktop.png" alt="Wellness Float 11 001 desktop preview" /></a><h3>Wellness Float 11 001</h3><p>Float therapy · minimal · restorative</p></td>
    <td width="50%" valign="top"><strong>More directions coming soon.</strong><p>New entries will use the same metadata, preview, provenance, and validation contract.</p></td>
  </tr>
</table>

See [all viewport previews](screenshots/README.md) for tablet and mobile
versions.

## Distribution model

The catalog is intentionally lightweight. Installing NoBlox does not download
this repository or every template. A NoBlox client reads the catalog, then
downloads only the selected, approved template artifact from a versioned
release or registry endpoint.

Each artifact must be immutable, checksum-addressed, and accompanied by a
completed license review before it is published for reuse. Current entries
are metadata and preview drafts while their source and asset redistribution
rights are reviewed. A `draft` entry is not a downloadable or production-ready
template.

## Repository layout

```text
catalog.json
templates/<template-id>/template.json
templates/<template-id>/{preview,tablet,mobile}.png
screenshots/<template-id>/{desktop,homepage,tablet,mobile}.png
```

Generated workspaces, local paths, caches, credentials, and raw capture
evidence do not belong in this public repository.

## Contributing

Every new template needs:

- stable ID and version;
- provenance and source URL;
- explicit artifact contents;
- license and redistribution evidence;
- framework and compatibility metadata;
- desktop, tablet, and mobile preview evidence;
- a deterministic checksum for the released artifact.

Until those checks pass, keep the catalog entry in `draft` or `restricted`.

## License

Repository metadata and original NoBlox contributions are licensed under the
[MIT License](LICENSE). A template's own source, design, and assets remain
subject to the provenance and license terms recorded in its metadata.
