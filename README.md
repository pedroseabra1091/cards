# Cards
Shuffle and deal cards built with Elixir.

**Features**:
- Create an array of playing cards
- Shuffle an array of playing cards
- Create a hand of cards
- Given a deck and a single card, figure out if the card is in the deck
- Save a collection of cards to a file on the local machine
- Load a collection of cards from the local machine

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `cards` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:cards, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/cards](https://hexdocs.pm/cards).

## Run
On the interactive shell, type `Cards.create_hand(hand_size))`. This will create a deck, shuffle and deal according to the defined hand size.

## Tests & Documentation

Run tests: `mix tests`.

Check documentation: `mix docs`.
