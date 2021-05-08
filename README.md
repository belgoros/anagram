# Anagram CLI application

This is an example of a CLI Ruby application `anagram` took from the [Programming Ruby 1.9 & 2.0 book](https://pragprog.com/titles/ruby4/programming-ruby-1-9-2-0-4th-edition/).

## Run

You can run the application from the projet root path as follows:

```ruby
ruby -I lib bin/anagram
```
and either pass in a path to the dictionary file with `-d` option or define a default one in `Anagram::Options` class for `DEFAULT_DICTIONARY` variable.
