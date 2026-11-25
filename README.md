# Cloudreve on Railway

Railway packaging for [Cloudreve](https://github.com/cloudreve/cloudreve). It builds on the official, unmodified image, pinned to a release, and adds only what Railway needs.

- Web app on port `5212`; attach a volume at `/cloudreve/data`.
- Database and Redis via `CR_CONF_Database.*` and `CR_CONF_Redis.*` variables (Postgres and Redis on Railway).
- The first account you register becomes the administrator.

## License

The files in this repository are MIT licensed (see `LICENSE`). Cloudreve itself is licensed separately by its authors; this repository does not include or modify its source code.
