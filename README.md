# Issues

**TODO: Add description**

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add issues to your list of dependencies in `mix.exs`:

        def deps do
          [{:issues, "~> 0.0.1"}]
        end

  2. Ensure issues is started before your application:

        def application do
          [applications: [:issues]]
        end


RUN:
mix run -e 'Issues.CLI.main(["elixir-lang", "elixir", "10"])'

TEST:
mix test


Package the program using mix:
​$ ​​mix​​ ​​escript.build

RUN:
$ ​​./issues​​ ​​elixir-lang​​ ​​elixir​​ ​​3​
