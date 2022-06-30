# Key - Value Store Application in Elixir

This is an [Elixir](https://elixir-lang.org/getting-started/introduction.html) application that works as a distributed key-value store.

> ⚠️ This is just a little application for me to learn Elixir.

### Development

In order to compile the code, run:

```sh
$ mix compile
```

Once the code has been compiled inside the `_build` folder, run:

```sh
$ iex -S mix
```

trying out the changes from an `iex` session.

### Testing

Mix comes with a testing framework called [ElixirUnit](https://elixir-lang.org/getting-started/introduction.html#elixirunit).

Write the tests in the [`test`](./test/) folder, with `.exs` suffix.

To execute the tests, run:

```sh
$ mix test
```