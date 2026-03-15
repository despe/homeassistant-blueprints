# Home Assistant Schneider Blueprints

This repository contains Home Assistant blueprints for Schneider Electric Zigbee cover modules.

The goal of these blueprints is to make it easier to control covers using physical wall buttons with ZHA events.

Compatible devices:

- Schneider Electric S520567W
- Home Assistant ZHA integration

---

## Available Blueprints

### Schneider ZHA Cover Buttons

Control a cover using the physical buttons of a Schneider wall module.

Features:

- Short press up → open cover
- Short press down → close cover
- Short press while moving → stop
- Long press up → configurable position
- Long press down → configurable position

Install the blueprint directly in Home Assistant:

https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/despe/ha-blueprints/blob/main/blueprints/automation/Schneider_ S520567W_cover/Schneider_ S520567W_cover.yaml

Blueprint source:

blueprints/automation/schneider/zha_cover_buttons.yaml

---

## Installation

1. Click the **Import Blueprint** button above
2. Select the Zigbee device
3. Select the cover entity
4. Configure your preferred positions

---

## Requirements

- Home Assistant
- ZHA integration
- Schneider cover module (S520567W)

---

## License

MIT License
