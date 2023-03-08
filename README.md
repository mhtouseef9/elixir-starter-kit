# Kinde ELixir SDK Starter Kit

Install erlang and elixir.

Update the deps, update path to the SDK in `mix.exs`
```elixir
{:kinde_management_api, path: "/path/to/kinde-elixir-sdk"}
```

Update :kinde_management_api config in `config/config.exs`.

Execute following in your terminal to run:

```
mix deps.get
mix phx.server
```

Use following routes to

- Login Client Credentials (/log-in)
- Claims (/claims)
- Claims PKCE (/claims-pkce)
- permissions (/permissions)
- User details (/user)
- Organization (/organization)
- All Tokens (/token)
- PKCE Login (/pkce-reg)