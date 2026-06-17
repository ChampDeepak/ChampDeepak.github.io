---
layout: post
title: "What is Json Actually?"
date: 2026-06-17
---

## What is JSON?

JSON is a language-independent data format that has its own grammar.

## Why is there a need for a language-independent data format?

Let's say there are two programs that need to exchange data with each other. For the sake of example, imagine we have a backend written in Go and a frontend written using React.

Now when a new user registers, React needs to send the signup details of the new user to the backend, and the backend needs to send a JWT token for token-based authentication.

To make this communication happen, both systems need a common format to exchange information. Otherwise, Programming languages cannot directly understand each other's in-memory objects.

So, to ensure smooth information exchange between systems irrespective of their language, we need a data format that is language-independent.

## How do language-independent data formats actually work in practice?

These data formats have their own set of rules, a.k.a. grammar. And yes, JSON has its own grammar.

This grammar ensures a uniform structure that can later be translated into language-specific entities by each language. For example, each language writes a JSON parser that converts JSON text into its own data structures.

So, to practically create a language-independent data format, we first define rules that the format must always adhere to, and then we write parsers to convert that format into language-specific entities.

```
JavaScript Object
   ↓ serialize
JSON text
   ↓ parse
Go struct
```

## What is the difference between a parser and a serializer?

- **Parser:** JSON → program objects
- **Serializer:** program objects → JSON

## A data format needs to follow all the following rules in order to be called JSON

- `{}` defines an object
- Must use double quotes for keys and string values
- `:` separates key and value
- `,` separates pairs
- Arrays must be represented using square brackets, like `[10, 20, 30]`
- Strings cannot contain raw line breaks
- Inside a JSON string you must write a newline as:

```
\n
```

NOT as an actual line break.

## Allowed value types

```
string
number
object
array
boolean
null
```

Nothing else.
