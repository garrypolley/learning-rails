# learning-rails

Going through the [Agile Web Development with Rails 4](http://pragprog.com/book/rails4/agile-web-development-with-rails-4) book.

I'll log my thoughts as I go.

## Chapters 1-4

The first few chapters of this book gave a simple introduction to ruby and a quick look into rails and what it can do.  I wrote about my thoughts on these chapters in a short post found over here: http://garrypolley.com/post/84381936563.

## Chapters 5 and 6

So far I am actually very impressed with the idea of convention over configuration.  The book starts you off with a simple app called Depot.  The goal for this app is to have buyers and sellers get and sell items.  Right off the bat the power of rails was/is shown with some simple commands that created all the models, views, and controllers needed for the "products" that would be bought and sold.  This somewhat small feature, is _awesome_.  It made the normal mundane part of app creation super easy and simple.  All that was needed was to actually style the page. Sane defaults is what Rails is built on and thus far I like it a lot.

## Chapter 7 (validation)

Validation is a feature of almost every framework.  Thus far I like how validation works with Rails.  It doesn't seem too different than most other things I have worked with.  However, I do really like the added 'negatives' to aide with readability in testing, (e.g. `assert product.invalid?`).  So far I do miss some of the parenthesis I had in Python land.  I think it adds to readability of code.  However, it seems Ruby programmers do not use them, so I'll write Ruby without them :frowning:.
