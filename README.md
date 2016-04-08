# Issues

Lists Issues on a Github project
When Erlang is installed run the package as;
   $ ​./issues elixir-lang elixir 3
   or
   $ .issues <account> <projectname> <number_of_issues>

Dave Thomas. Programming Elixir 1.2 (Kindle Locations 6577-6580). The Pragmatic Bookshelf, LLC. 

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

