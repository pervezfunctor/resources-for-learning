 (Today, most programming languages, if not all, support functional programming. Programmers started looking at FP, after failing to create concurrent applications using the usual imperative, object oriented techniques and realized the benefits of using functional programming.

Unfortunately, it seems like most of my students are either completely unaware of functional programming, or have lot's misconceptions about it. To be honest it is really sad. This email tries to help you fix the problem.

Functional does NOT mean procedural. C is NOT a functional language.

I believe a language supports functional programming if

* immutable values are possible and immutable collections are available.
* functions are values, allowing higher order functions.

This means that you could learn and write functional code in almost every language today(except perhaps C). I would highly encourage you to give FP a chance using your own language of choice, if you cannot afford to learn a new language.

There's more to FP than just that, though it's a good start. You could read [Why FP matters pdf](http://worrydream.com/refs/Hughes-WhyFunctionalProgrammingMatters.pdf) to understand a bit more about FP.

Some additional proof of why FP matters

* Swift, the new language by apple, is mostly inspired by functional languages.
* Rust, a replacement for C++, still a work in progress, has excellent FP support. For example, all values are immutable by default.
* C# supports immutable collections, LINQ and might support pattern matching in future.
* C++ adds lambda expressions in C++11.
* Java 8 adds lambda expressions, streams and a lot more.
* Scala, Clojure and to some extend F# have gained immensely in popularity in the past few years. Most large scala companies(twitter, netflix, linkedin etc) today, use Scala.
* One of  the most famous javascript libraries(second only to angular?), react from facebook is based on FP principles.
* Haskell is one of the most talked languages today. Most well aware programmers either know haskell, or have it on their TODO list.

In short almost every language today has some support for FP(except C). Most modern languages, modern frameworks and libraries are based on FP. I highly recommend you follow some good programmers and spend some time on twitter.

Some optional FP features

* functions as first class citizens supporting composition
* sum types and product types
* pattern matching
* lazy evaluation
* persistent collections - vectors, maps, sets, lists
* static typing - parametric and adhoc polymorphism

### .NET programmers

.NET today supports immutable collections and had support for higher order functions(LINQ) for a very long time. Next version of C# might even support records and pattern matching. C# has been moving in the direction of FP for a long time. Just use immutable collections in .NET and use LINQ, you are doing FP! I am sure you would like to learn more about it. Please also understand that only using LINQ operators is not FP. There's more to it than just that. If you want to stick to C#, still learn functional programming then the following two books would be useful

* [Functional Programming in C#](http://www.amazon.com/Functional-Programming-Classic-Techniques-Projects/dp/0470744588)
* [Real-World Functional Programming](http://www.amazon.com/Real-World-Functional-Programming-With-Examples/dp/1933988924)

If you can afford to learn another programming language which works on .NET, F# is an excellent choice. Remember that, most C# features after 1.0, have been inspired by F#. It's perhaps the simplest language to learn functional programming well. Not only that, you really have some excellent resources available.

* [F# for fun and profit webstie](http://fsharpforfunandprofit.com) - This is an excellent resource. Just skim over a few topics, to get a taste of F# and FP.

* [Functional Programming Using F#](http://www.amazon.com/Functional-Programming-Using-Michael-Hansen-ebook/dp/B00CARIB52) - This is the best introduction to F#, irrespective of your prior experience. Fortunately for .NET developers, this is written in F#.

### Web developers

Many javascript developers, write functional code. In javascript community, FP is more famous than any other paradigm. The following resources would be really helpful to get you up and started in no time.

* [Javascript allonge ](https://leanpub.com/javascript-allonge/read) - One of my favourite books, irrespective of technology.

* [Coffeescript ristretto](https://leanpub.com/coffeescript-ristretto/read) - Another excellent book by the same author, but in coffeescript.

*[Functional Javascript](http://www.amazon.com/Functional-JavaScript-Introducing-Programming-Underscore-js/dp/1449360726) - A classic, by the author of "The Joy of Clojure". It's a difficult read, but eventually when you are done, you will be a much better programmer.

Have a look at [immutable-js](https://github.com/facebook/immutable-js), [react](http://facebook.github.io/react) and [ramda](https://github.com/CrossEye/ramda) libraries. Even [underscore](http://underscorejs.org)/[lodash](https://lodash.com) should be fine.

Please also keep in mind that, by learning FP techniques in javascript, you learn to write simple, succinct, elegant and more robust code even in an object oriented setting. Your code would be far better than before, it will make you a much better javascript developer. You will appreciate javascript more, and perhaps you would end up enjoying writing javascript code, for a change.

Have a look at coffeescript too! It makes FP more natural.

### C++ programmers

* If you are a C++ developer, you might already be writing FP, without realizing it. If you are using standard C++ library, you are mostly doing FP. Unfortunately, it's harder to learn FP with C++, it's harder to write C++ code with immutable values/collections. In any case the following resources should be helpful. Remember, they aren't easy. Easiest would be to learn rust.

* [Functional C++ blog](http://functionalcpp.wordpress.com)
* [Boost.Range](http://www.boost.org/doc/libs/master/libs/range/doc/html/index.html)
* [FTL](https://github.com/beark/ftl)
* [Introduction to functional programming with C++ - youtube](https://www.youtube.com/watch?v=uHFUpFhWGJs)
* [Functional data structures in C++ - youtube](https://www.youtube.com/watch?v=OsB09djvfl4)
If you are interested in FP, and you don't mind learning another language, only that it should be fast and native, [Rust](http://doc.rust-lang.org/guide.html) is an excellent option, with immutable values as the default, support for pattern matching, functions as first class citizen and parametric and ad-hoc polymorphism. This goes to show how important FP has become, a native language created for writing safe performant code, supports FP out of the box.

###Everyone

If you could see the point of FP, I am sure you would like to invest in learning it better, using the best functional programming language. Haskell, definitely is the best choice. Do yourself a favour, learn at least the basics of haskell using the following resources.

*[Learn You a Haskell for great good](http://learnyouahaskell.com) - Excellent simple, free online resource teaching haskell and functional programming. First few chapters should be enough.

*[Programming in Haskell](http://www.amazon.com/Programming-Haskell-Graham-Hutton/dp/0521692695/ref=sr_1_11?ie=UTF8&qid=1413085925&sr=8-11&keywords=haskell) - A gentle 150 odd pages introduction to functional programming using haskell. Almost anyone can read this book. I highly recommend you buy this one.

*[C9 haskell videos](http://channel9.msdn.com/Series/C9-Lectures-Erik-Meijer-Functional-Programming-Fundamentals/Lecture-Series-Erik-Meijer-Functional-Programming-Fundamentals-Chapter-1) 13 videos by entertaining Eric Meijer, perhaps might the best way to learn functional programming if you do not like reading a book. He is the creator of LINQ.
