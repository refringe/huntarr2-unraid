<p align="center">
  <img src="https://raw.githubusercontent.com/refringe/huntarr2/main/.github/images/banner.png" alt="Huntarr2" />
</p>

Unraid Community Applications template repository for [Huntarr2](https://github.com/refringe/huntarr2).

## Installation

### Community Applications (recommended)

Search for **Huntarr2** in the Unraid Community Applications store.

### Manual

1. Open the Unraid web interface.
2. Navigate to **Docker** > **Template Repositories**.
3. Add the following URL:
   ```
   https://github.com/refringe/huntarr2-unraid
   ```
4. Click **Save**, then create a new container using the Huntarr2 template.

## Configuration

| Parameter | Default | Description |
|-----------|---------|-------------|
| WebUI Port | `9706` | Port for the Huntarr2 web interface |
| Config Path | `/mnt/user/appdata/huntarr2` | Persistent storage for database and configuration |
| PUID | `99` | User ID for file ownership |
| PGID | `100` | Group ID for file ownership |
| TZ | `America/New_York` | Container timezone |
| LOG_LEVEL | `info` | Log verbosity (advanced) |
| AUTH_USERNAME | *(empty)* | HTTP Basic Auth username (advanced) |
| AUTH_PASSWORD | *(empty)* | HTTP Basic Auth password (advanced) |
| ENCRYPTION_KEY | *(auto-generated)* | AES-256-GCM encryption key (advanced) |

## Support

Open an issue on the [Huntarr2 repository](https://github.com/refringe/huntarr2/issues).
