# Command Line Calculator #

Den här uppgiften går ut på att skriva ett enkel kalkylator som körs i kommandoprompten

Du skall skriva ett program (`calculate.rb`) med fyra funktioner: ` add`, `divide`, `multiply`och `subtract`. Alla funktionerna tar två tal **som argument** och **returnerar** resultatet av uträkningen.

Programmet ska ta data direkt från kommandoprompten, med hjälp av [`ARGV`](https://www.codecademy.com/articles/ruby-command-line-argv)

Programmet använder sen `ARGV` för att avgöra vilken av funktionerna som ska anropas, anropa funktionen, och sen skriva ut resultatet funktionen returnerar

### Exempel ###

I kommandoprompten:

```ruby
ruby calculate.rb 4 - 6
>>> -2

ruby calculate.rb 13 + 37
>>> 50
```


### Bonusbana  ###

Modifiera din kod så att du kan utföra flera beräkningar direkt från kommandoprompten, t.ex 

```ruby
ruby calculate.rb 4 + 3 * 2 - 6
>>> 4
```

### Länkar ###

Läs mer om hur `ARGV` fungerar:

- [CodeAcademy](https://www.codecademy.com/articles/ruby-command-line-argv)
- [Learn Ruby the Hard Way - Exercise 14: Prompting and Passing](https://learnrubythehardway.org/book/ex14.html)

`ARGV` är en inte egentligen en variabel, utan är en *konstant* (en variabel som inte får byta värde). Läs mer om konstanter i ruby:

* [Ruby Learning - Ruby Constants](http://rubylearning.com/satishtalim/ruby_constants.html)