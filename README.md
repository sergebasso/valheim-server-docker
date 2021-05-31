# Valheim Server

## Usage

1. Install Docker Desktop
2. Open PowerShell
3. Copy ``.env.template`` to ``.env`` and configure
4. Bring up the stack with ``docker-compose up``

## Status pages

- Valheim: http://127.0.0.1/
- Supervisor: http://127.0.0.1:9001/

## Worlds

Worlds are saved to ``./config/worlds/``.

## Backups

Destination configured using the ``HOST_BACKUPS_DIRECTORY`` variable in ``.env``.

## Valheim Plus

Enabled using the ``VALHEIM_PLUS`` variable in ``.env``. Configuration is saved to ``./config/valheimplus/valheim_plus.cfg``.
