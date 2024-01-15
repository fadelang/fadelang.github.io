---
sidebar_position: 1
---

# Hello, World!

The infamous hello world program is one of the best programs to test if
everything works. Luft keeps the spirit of this and makes it really easy to
write.

## The program

The hello world program is just three lines long, and can even be written in one
line.

```ts
main(): {
    println("Hello, World!");
}
```

## How does this work?

The `main` function is the entry point of the program. The `println` function,
called from the main function, resides in the `luft::process` module.

The `luft::process::println` function is one of the
[implicitly imported](#) functions since it's so commonly used and it would be
too tedious to import it every time.

```ts

```

