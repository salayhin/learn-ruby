## Advanced String Operations

- split(p1 = v1, p2 = v2) public

Divides str into substrings based on a delimiter, returning an array of these substrings.

`'Fear is the path to the dark side'.split(' ')`

> Output:

`["Fear", "is", "the", "path", "to", "the", "dark", "side"]`

- Concatenating Strings

You can create a new string by adding two strings together in Ruby, just like most other languages.
> 'Ruby' + 'Monk'

> "Ruby".concat("Monk")

- You can use '<<' just like '+', but in this case the String object 'Monk' will be appended to the object represented by 'Ruby' itself. In the first case of using '+', the original string is not modified, as a third string 'RubyMonk' is created. This can make a huge difference in your memory utilization, if you are doing really large scale string manipulations

> 'Ruby' << 'Monk'

- Replacing a substring

`"I should look into your problem when I get time".sub('I','We')`

> Output:

`We should look into your problem when I get time`

- gsub

Returns a copy of str with the all occurrences of pattern substituted for the second argument. The pattern is typically a Regexp; if given as a String, any regular expression metacharacters it contains will be interpreted literally, e.g. ‘\d’ will match a backlash followed by ‘d’, instead of a digit.

`"I should look into your problem when I get time".gsub('I','We')`

> Output:

`We should look into your problem when We get time`

`'RubyMonk'.gsub(/[aeiou]/,'1')`

> Output:

`R1byM1nk`

`'RubyMonk Is Pretty Brilliant'.gsub(/[A-Z]/,'0')`

> Output:

`0uby0onk 0s 0retty 0rilliant`

- Find a substring using RegEx (match)

Converts pattern to a Regexp (if it isn’t already one), then invokes its match method on str. If the second parameter is present, it specifies the position in the string to begin the search.

> ```
'hello'.match('(.)\1')      #=> #<MatchData "ll" 1:"l">
'hello'.match('(.)\1')[0]   #=> "ll"
'hello'.match(/(.)\1/)[0]   #=> "ll"
'hello'.match('xx')         #=> nil
```

