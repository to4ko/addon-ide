## v0.1.0 [26.09.2026]

- Add-on config moved from config.json to config.yaml
- Fixed Supervisor deprecation warnings:
  - `auto_uart` replaced with `uart`
  - map `config` replaced with `homeassistant_config`, `addons` with `local_apps`
    (still mounted at `/config` and `/addons`, so the workspace layout is unchanged)
  - dropped deprecated architectures `armhf`, `armv7`, `i386`


## v0.0.1 [02.05.2024]

- Initial build
