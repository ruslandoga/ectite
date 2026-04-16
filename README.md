SQLite adapter for Ecto.

```elixir
defmodule MyApp.Repo do
  use Ecto.Repo, adapter: LitEcto, otp_app: :my_app
end
```
