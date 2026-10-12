# Sony Songpal with grouping

Fork of the Home Assistant core `songpal` integration that adds speaker grouping
(`media_player.join` / `media_player.unjoin`) via the devices' UPnP group service.

Installing this overrides the built-in `songpal` integration; existing config
entries keep working. Requires Home Assistant 2026.10.0 or newer and SSDP
(part of `default_config`).

## Install via HACS

HACS → ⋮ → Custom repositories → add this repo's URL with type "Integration",
then install "Sony Songpal (with grouping)" and restart Home Assistant.

To go back to the built-in integration, remove it in HACS and restart.
