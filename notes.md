# Elixir Leaning

- If I have a big number like 1000000000, I can represent it like 1_000_000_000 without problems
- / returns a float and div returns an int
- to concatenate strings: "Jonas" <> " with Johanes"
- variables: 
name = "Jonas" 
lastName = "Johanson"
- to concatenate variables: "#{name} #{lastName}"
- You use an atom when you have a string that you may need to use at different places
- Booleans: True and False
- Nil: null value
Under the hood, true, false and nil are all atoms (:true, :false, :nil)
- Falsy values: False, Nil
- Truthy values: everything else

- String.  <- A module that has a lot of functions inside
- List. 
- Node x Elixir:
"jonas".length x String.length("jonas")
- /2 or /1 in front of a function indicates how many arguments that function takes
- If it has an exclamation before it, it will raise an error if it's wrong
- Tuples are sequentially saved in memory
- Acces an element of the tuple: elem({1,2}, 0) = 1
- We use tuples to read File.read results
- String.split("1    2 33  3 4", trim: true)


