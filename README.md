# BankAPI

This project is a simple HTTP API for a bank that will allow us to open and close accounts, deposit and withdraw funds and transfer them between accounts.

This is me trying to understand how event sourcing works in Elixir. Im following this article named [Event Sourcing With Elixir](https://blog.nootch.net/post/event-sourcing-with-elixir/). Nice work!!!

I’m using the excellent [commanded](https://github.com/commanded/commanded) library for the article series, which is the center around building a very simple API for a bank.

Also, this project is covering Aggregates, Commands, Events, Projections and Projectors, supervised Process Managers, Routers, Commanded middleware for auditing and validation, and of course testing for the API’s functionality.

To start your Phoenix server:

- Install dependencies with `mix deps.get`
- Create and migrate your database with `mix ecto.setup`
- Start Phoenix endpoint with `mix phx.server` or inside IEx with `iex -S mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

- Official website: https://www.phoenixframework.org/
- Guides: https://hexdocs.pm/phoenix/overview.html
- Docs: https://hexdocs.pm/phoenix
- Forum: https://elixirforum.com/c/phoenix-forum
- Source: https://github.com/phoenixframework/phoenix
