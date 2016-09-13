# Ruby Tricks, Idiomatic Ruby, Refactorings and Best Practices

> Do you know why experienced Ruby programmers tend to reach for basic collections
> and hashes while programmers from other languages go for more specialized classes?
> Do you know the difference between strip, chop, and chomp; and why there are three
> such similar methods when apparently one might suffice (Not to mention lstrip and
> rstrip!)? Do you know the downsides of dynamic typing? Do you know why the differences
> between strings and symbols get so blurry, even to experienced Ruby developers?
> How about metaprogramming? What the heck is an eigenclass? How about
> protected methods? Do you know what they’re really about? Really? Are you sure?
[Eloquent Ruby](http://www.amazon.com/Eloquent-Ruby-Addison-Wesley-Professional/dp/0321584104)

> Absolutely the best way to learn to write idiomatic Ruby code is to read idiomatic Ruby code. [Eloquent Ruby](http://www.amazon.com/Eloquent-Ruby-Addison-Wesley-Professional/dp/0321584104)

This repository aims to help everyone write more idiomatic, clean, and tricky ruby code and also document good refactoring techniques. You can add your own technique or paste it from some website. Do not forget the source, of course. All the tricks are in the /tricks folder.

For the sake of clarity, you should paste in the markdown format. At the end, if the code is not your own, paste a reference to the author and source of the technique.

## [Tricks](tricks.md)

In this part we can review some obscure or awesome features from the and the standard ruby library which we normally forget.

* [Alphanumeric incrementing](tricks/alphanumeric-incrementing.md)
* [Associative arrays](tricks/associative-arrays.md)
* [At exit method](tricks/at-exit-method.md)
* [Autovivification](tricks/autovivification.md)
* [Blocks can take blocks](tricks/blocks-can-take-blocks.md)
* [Bubbling up thread errors](tricks/bubbling-up-thread-errors.md)
* [Case on ranges](tricks/case-on-ranges.md)
* [Count all objects](tricks/count-all-objects.md)
* [Cycle](tricks/cycle.md)
* [Data](tricks/data.md)
* [Easiest database pstore](tricks/easiest-database-pstore.md)
* [Easiest database pstore yaml](tricks/easiest-database-pstore-yaml.md)
* [Enable garbage collector profiler](tricks/enable-garbage-collector-profiler.md)
* [Enable ruby warnings](tricks/enable-ruby-warnings.md)
* [Fast memoization fibonacci](tricks/fast-memoization-fibonacci.md)
* [Fetch data](tricks/fetch-data.md)
* [Get random data](tricks/get-random-data.md)
* [Head tail](tricks/head-tail.md)
* [Inject](tricks/inject.md)
* [Inspecting the source with script lines](tricks/inspecting-the-source-with-script-lines.md)
* [Iterating over specific types](tricks/iterating-over-specific-types.md)
* [Lambda your own syntax](tricks/lambda-your-own-syntax.md)
* [Memoization](tricks/memoization.md)
* [Print formatted with debug](tricks/print-formatted-with-debug.md)
* [Ruby debug flag](tricks/ruby-debug-flag.md)
* [Shortcut variable interpolation](tricks/shortcut-variable-interpolation.md)
* [Single instance running](tricks/single-instance-running.md)
* [Smalltalk conditionals](tricks/smalltalk-conditionals.md)
* [Splat operator](tricks/splat-operator.md)
* [Stab operator](tricks/stab-operator.md)
* [Struct without assignment](tricks/struct-without-assignment.md)
* [Super magic keyword](tricks/super-magic-keyword.md)
* [Super magic keyword2](tricks/super-magic-keyword2.md)
* [Super magic keyword3](tricks/super-magic-keyword3.md)
* [Super magic keyword4](tricks/super-magic-keyword4.md)
* [Super magic keyword5](tricks/super-magic-keyword5.md)
* [Tail call](tricks/tail-call.md)
* [Trigger irb as needed](tricks/trigger-irb-as-needed.md)
* [Unfreeze objects with fiddle](tricks/unfreeze-objects-with-fiddle.md)
* [Unused variable format](tricks/unused-variable-format.md)
* [Variables from a regex](tricks/variables-from-a-regex.md)
* [Zip](tricks/zip.md)
* [Introspecting Block Parameters](tricks/introspecting_block_parameters.md)
* [How to add uniq value to array](tricks/add_uniq_value_to_array.md)

## [Idiomatic Ruby](idiomatic_ruby.md)

You can write Ruby code, but it can sometimes look like Java code. Here you can find some tips to write more naturally and take advantage of idiomatic Ruby.

 * [Each vs map](idiomatic_ruby/each_vs_map.md)
 * [Conditional assignment](idiomatic_ruby/conditional_assignment.md)
 * [Combine operation over collections (enumerables)](idiomatic_ruby/combine_elements_in_collection.md)
 * [Array of Strings or Symbols](idiomatic_ruby/array_of_strings_symbols.md)
 * [Multiple Assignment](idiomatic_ruby/multiple_assignment.md)
 * [Use Symbol to_proc](idiomatic_ruby/use_symbol_to_proc.md)
 * [Array Sample (enumerables)](idiomatic_ruby/array_sample.md)
 * [Use Fixnum#times](idiomatic_ruby/use_times.md)
 * [Implicit Return](idiomatic_ruby/implicit_return.md)


## [Refactorings](refactorings.md)

Small (and big) improvements you can apply to your code and improve it's readability and maintenance. Change the internal structure of the code without changing it's behaviour.


* [Conditionals when object is nil](refactorings/conditionals_when_object_is_nil.md)
* [Switch case with Hashes](refactorings/case_with_hashes.md)

## [Best Practices](best_practices.md)

If you keep your house cleaned constantly you'll never need to waste a weekend cleaning it. The same applies to your code. Be disciplined and keep your code looking good with those tips.

* [rescue => Exception e](best_practices/using_exception_e.md)

## Contributors

A big thanks to the following [people](https://github.com/franzejr/best-ruby/graphs/contributors)

## Contributing

1. [Fork it](https://github.com/franzejr/best-ruby)
2. Create a branch with your idea: `git checkout -b my-idea`
3. Check in which category it should be: best practice, idiomatic ruby, refactorying or trick. If you don't know, please open an issue and ask.
4. Add your idea to the collection of `.md` files in the correct folder (tricks, refactorings, idiomatic_ruby or best_practices) folder
5. Commit your changes: `git commit -am 'Add my idea'`
6. Push to the branch: `git push origin my-idea`
7. Create a new Pull Request and explain your technique in the markdown file
