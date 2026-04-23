# Camtasia (camtasia)

Camtasia is a screen recording and video editing software by TechSmith that allows users to create professional videos, tutorials, and presentations with built-in editing tools, effects, and media assets. Camtasia itself does not publish a public REST API, but it integrates tightly with TechSmith Screencast for sharing, and TechSmith publishes a public Screencast oEmbed API plus the Camtasia Screen Recorder SDK for embedding recording capabilities into third-party applications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/camtasia/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

 - Screen Recording, Video Editing, Tutorial Creation, E-Learning, Screencast, oEmbed, SDK

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-23

## APIs

### TechSmith Screencast oEmbed API

Public oEmbed API for TechSmith Screencast (app.screencast.com), the cloud destination where Camtasia videos and images are shared. The oEmbed endpoint returns embed HTML, thumbnail, and metadata for a given Screencast content URL, letting content platforms and CMSes render Screencast shares inline the same way they render YouTube or Vimeo. Documentation is maintained in a public GitHub repository.

**Human URL:** [https://github.com/TechSmith/screencast-public-api-docs](https://github.com/TechSmith/screencast-public-api-docs)

#### Tags

 - oEmbed, Screencast, Embedding, Video

#### Properties

- [Documentation](https://github.com/TechSmith/screencast-public-api-docs/blob/main/sections/oembed.md)
- [Repository](https://github.com/TechSmith/screencast-public-api-docs)
- [JSON-LD Context](json-ld/camtasia-context.jsonld)

### Camtasia Screen Recorder SDK

A developer toolkit from TechSmith that lets developers embed reliable high-quality screen, webcam, and audio recording into their own applications. The SDK exposes APIs to configure, start, stop, and automate recording workflows, and to capture cursor and system audio alongside the screen.

**Human URL:** [https://www.techsmith.com/camtasia.html](https://www.techsmith.com/camtasia.html)

#### Tags

 - SDK, Screen Recording, Embedded

#### Properties

- [Product Page](https://www.techsmith.com/camtasia.html)

## Use Cases

- Publishing platforms and CMSes that want to auto-embed Screencast-hosted tutorials the way they embed YouTube videos, using the oEmbed API.
- E-learning products that embed Camtasia Screen Recorder SDK to offer in-app tutorial capture.
- Support and remote-assist tools that capture screen, webcam, cursor, and audio through the SDK.
- Content operations teams indexing Camtasia Screencast shares into internal knowledge bases using oEmbed metadata.

## Common Properties

- [Website](https://www.techsmith.com/camtasia.html)
- [Screencast](https://www.techsmith.com/screencast/)
- [Getting Started](https://www.techsmith.com/learn/camtasia/)
- [Blog](https://www.techsmith.com/blog/category/camtasia/)
- [Support](https://support.techsmith.com)
- [Public API Repository](https://github.com/TechSmith/screencast-public-api-docs)
- [Terms of Service](https://www.techsmith.com/terms.html)
- [Privacy Policy](https://www.techsmith.com/privacy.html)
- [JSON-LD Context](json-ld/camtasia-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
