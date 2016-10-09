## Installation

The package can be installed as:

  1. Add `upyun` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:upyun, github: "davidqhr/elixir-upyun"}]
    end
    ```

  2. Ensure `upyun` is started before your application:

    ```elixir
    def application do
      [applications: [:upyun]]
    end
    ```

