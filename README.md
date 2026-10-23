# meta-rdkb-runtime

`meta-rdkb-runtime` is a Yocto Project / OpenEmbedded layer containing runtime metadata for RDK-based broadband devices.

The layer provides the recipes, configuration, and integration required to include RDK runtime components in Yocto-based broadband images.

## Scope

This layer may contain:

- RDK runtime component recipes
- Service and daemon integration
- systemd unit files and configuration
- Runtime dependencies
- RDK-specific configuration
- Package groups
- Image integration metadata
- Platform-independent overrides and settings

The goal is to keep RDK runtime and software integration separate from hardware-specific BSP metadata.

## Layer Structure

Typical contents include:

```text
meta-rdk-runtime/
├── conf/
│   └── layer.conf
├── recipes-rdk/
├── recipes-core/
├── recipes-support/
└── packagegroups/
