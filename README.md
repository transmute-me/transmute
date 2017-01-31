# Transmute

Transmute is an application to _transmute_ your laptop from a new piece of
hardware direct from the manufacturer into *your* laptop, complete with
applications and configuration that you want!

## Usage

`transmute my_laptop.yaml`

my_laptop.yaml may lok like:

~~~yaml
git:
  # implicit source
  username: Chris MacNaughton
  email: chris@example.com
atom:
  source: https://github.com/transmute-me/transmute-atom
  plugins:
    - language-rust
~~~
