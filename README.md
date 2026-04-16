SQLite adapter for Ecto.

```elixir
defmodule MyApp.Repo do
  use Ecto.Repo, adapter: Ectite, otp_app: :my_app
end
```
