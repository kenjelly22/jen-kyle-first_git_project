# My 4 Favorite Ruby methods

### `downcase` (String)

Changes all letters to their lowercase form if not already

```ruby
"ABC".downcase #=> "abc"
```

### `sort` (Array)

Sorts an array by the values from least to greatest

```ruby
[3,1,6,3].sort #=> [1,3,3,6]
```

### `values`(Hash)

Return an array of the values of all of the keys in a hash

```ruby
{
    hi: "hello",
    bye: "goodbye"
}.values #=> ['hello', 'goodbye']
```

### `odd?` (Integer)

Boolean value returning true if the number is odd or false if even

```ruby
3.odd? #=> true
```
