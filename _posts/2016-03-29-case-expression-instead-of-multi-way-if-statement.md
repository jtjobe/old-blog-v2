---
layout: post
title: "Refactor Multi-Way Ifs with Case Statements for Readability"
author: me
modified:
excerpt: "Use case expressions in place of messy if/else statements for readable, self-documenting code"
tags: []
---

If you're not using case statements, you should be. 

David Thomas, author of Programming Ruby, calls the case expression "a powerful beast: a multiway if on steroids" (1).

In less colorful words: anytime you have a long, messy if/else statement you might want to consider using a case expression instead.

Take the following three code snippets:

#### 1) Messy If/Else Statement

{% gist jtjobe/4f07f28dc7b28aadda137bf38598eb7a %}

####  2) Refactored with Case Statement

{% gist jtjobe/a5268be86f30a07d1d130724f7feeb3e %}

####  3) Refactored to One-Line Expressions

{% gist jtjobe/a7945c4836514208e76ef5f42dcd2dbd %}

## Simple but Powerful

The code above is simple enough that quickly making sense of what's happening in the multiway if isn't difficult. However, in more complex use cases this same refactoring can be the difference between easy to read self-documenting code and an unclear mess that takes extra time to decipher.




1. Thomas, David. Programming Ruby. Raleigh, N.C.: Pragmatic Bookshelf, 2005.