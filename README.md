# Phoenix

Example [Phoenix](https://www.phoenixframework.org/) app. Phoenix is a web framework for Elixir, known for real-time features with LiveView and channels.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Railpack |
| Project directory | `/` |
| Install command | leave empty |
| Build command | leave empty |
| Start command | leave empty |
| Application port | `4000` |
| Health check path | `/` |

## Environment variables

| Variable | Value |
| --- | --- |
| `PHX_HOST` | app domain, for example `app.example.com` |
| `SECRET_KEY_BASE` | output of `openssl rand -base64 48` |

## <a name="dev"></a>Run locally

```bash
# install dependencies
mix setup

# start the app
mix phx.server
```
