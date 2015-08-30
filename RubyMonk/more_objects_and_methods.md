## More Objects and Methods

- You simply call the methods method on them.
`1.methods`
> output:

```
[:to_s, :-@, :+, :-, :*, :/, :div, :%, :modulo, :divmod, :fdiv, :**, :abs, :magnitude, :==, :===, :<=>, :>, :>=, :<, :<=, :~, :&, :|, :^, :[], :<<, :>>, :to_f, :size, :zero?, :odd?, :even?, :succ, :to_json, :integer?, :upto, :downto, :times, :next, :pred, :chr, :ord, :to_i, :to_int, :floor, :ceil, :truncate, :round, :gcd, :lcm, :gcdlcm, :numerator, :denominator, :to_r, :rationalize, :to_bn, :months, :month, :years, :year, :multiple_of?, :ordinalize, :taguri=, :taguri, :to_yaml, :singleton_method_added, :coerce, :i, :+@, :eql?, :quo, :remainder, :real?, :nonzero?, :step, :to_c, :real, :imaginary, :imag, :abs2, :arg, :angle, :phase, :rectangular, :rect, :polar, :conjugate, :conj, :blank?, :html_safe?, :duplicable?, :pretty_print_cycle, :pretty_print, :seconds, :second, :minutes, :minute, :hours, :hour, :days, :day, :weeks, :week, :fortnights, :fortnight, :ago, :until, :since, :from_now, :bytes, :byte, :kilobytes, :kilobyte, :megabytes, :megabyte, :gigabytes, :gigabyte, :terabytes, :terabyte, :petabytes, :petabyte, :exabytes, :exabyte, :as_json, :encode_json, :between?, :psych_to_yaml, :to_yaml_properties, :present?, :presence, :acts_like?, :try, :in?, :to_param, :instance_values, :instance_variable_names, :with_options, :to_query, :`, :to_yaml_style, :syck_to_yaml, :pretty_print_instance_variables, :pretty_print_inspect, :shared_context, :shared_examples, :share_examples_for, :shared_examples_for, :share_as, :describe, :require_or_load, :require_dependency, :require_association, :load_dependency, :load, :require, :unloadable, :nil?, :=~, :!~, :hash, :class, :singleton_class, :clone, :dup, :initialize_dup, :initialize_clone, :taint, :tainted?, :untaint, :untrust, :untrusted?, :trust, :freeze, :frozen?, :inspect, :methods, :singleton_methods, :protected_methods, :private_methods, :public_methods, :instance_variables, :instance_variable_get, :instance_variable_set, :instance_variable_defined?, :instance_of?, :kind_of?, :is_a?, :tap, :send, :public_send, :respond_to?, :respond_to_missing?, :extend, :at_exit, :display, :method, :public_method, :define_singleton_method, :__id__, :object_id, :to_enum, :enum_for, :gem, :silence_warnings, :enable_warnings, :with_warnings, :silence_stderr, :silence_stream, :suppress, :capture, :silence, :quietly, :psych_y, :class_eval, :debugger, :should, :should_not, :pretty_inspect, :suppress_warnings, :equal?, :!, :!=, :instance_eval, :instance_exec, :__send__]
```

- Here's an example of an argument to the method index, which finds the position of the argument in the array:

> Example Code:

 `['rock','paper','scissors'].index('paper')`
 > Output:
 `1`