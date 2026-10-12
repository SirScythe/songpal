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

## Credits

Based on the [`songpal` integration](https://www.home-assistant.io/integrations/songpal)
from [Home Assistant core](https://github.com/home-assistant/core), originally
written by [@rytilahti](https://github.com/rytilahti) (who also maintains the
underlying [python-songpal](https://github.com/rytilahti/python-songpal) library)
and [@shenxn](https://github.com/shenxn). This fork adds speaker grouping and is
not maintained by them; please report issues
[here](https://github.com/SirScythe/songpal/issues).

Licensed under the Apache License 2.0, like Home Assistant core (see `LICENSE.md`).
Modified from the original: `media_player.py`, `const.py`, `strings.json` and
`manifest.json`.
