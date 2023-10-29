# Identicon

## Prerequisites

Before getting started, make sure you have the following prerequisites installed on your system:

- [Elixir](https://elixir-lang.org/install.html)
- [Erlang/OTP](https://www.erlang.org/downloads)
- [Mix](https://hexdocs.pm/mix/Mix.html)

## Installation

### Elixir

You can install Elixir by following the instructions for your specific platform:

- **Linux**: Use your package manager (e.g., apt, dnf, or pacman).
- **macOS**: Use [Homebrew](https://elixir-lang.org/install.html#mac-os-x).
- **Windows**: Download the installer from the [official website](https://elixir-lang.org/install.html#windows).

To verify your Elixir installation, run:

```bash
elixir --version
```
## Example

### To run

```
mix deps.get
iex -S mix
```

### To Generate Identicon
```
iex> Identicon.main("avatar")
```
The terminal should give you a glorious
```
:ok
```
And you should have a shiny new file called `avatar.png`, which should lookl like this:
![avatar identicon](./avatar.png)


