## Introduction to Strings

- `'RubyMonk'.length`

> Output:

`8`

## String Basics

- String Interpolation

> `def string_length_interpolater(incoming_string)
  		"The string you just gave me has a length of #{incoming_string.length}"
   end`

- The essential difference between using single or double quotes is that double quotes allow for escape sequences while single quotes do not. What you saw above is one such example. “\n” is interpreted as a new line and appears as a new line when rendered to the user, whereas '\n' displays the actual escape sequence to the user.

- Incude a word in a string

`"[Luke:] I can’t believe it. [Yoda:] That is why you fail.".include? 'Yoda'`

> Output:

`true`

- Start with a string

`"Ruby is a beautiful language".start_with? 'Ruby'`

> Output:

`true`

- End with a string

`"I can't work with any other language but Ruby".end_with? 'Ruby'`

> Output:

`true`

-  It is conventional in Ruby to have '?' at the end of the method if that method returns only boolean values.

- Index of a string

`"I am a Rubyist".index 'R'`

> Output:

`7`

- To Upper

> `puts 'i am in lowercase'.upcase #=> 'I AM IN LOWERCASE'`

- To Lower

`'This is Mixed CASE'.downcase`

> Output:

`this is mixed case`

-  Ruby provides a way to swap the case of every character in it

`"ThiS iS A vErY ComPlEx SenTeNcE".swapcase`

> Output:

`tHIs Is a VeRy cOMpLeX sENtEnCe`

