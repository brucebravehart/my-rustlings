# Rustlings — Hands-on Rust Exercises

A focused collection of small, incremental Rust exercises and solutions intended to teach and demonstrate practical Rust skills to engineers and recruiters.

- Practical, task-sized problems that show how a developer thinks in Rust.
- Exercises cover core Rust concepts: ownership & borrowing, lifetimes, error handling, generics, traits, structs/enums, collections, iterators, smart pointers, concurrency (threads), macros, and testing.

```
cargo test
```

- Look for: clear ownership/borrowing, error handling (Result/Option), concise use of iterators, appropriate use of generics/traits, and test coverage.

Repository layout

- `exercises/` : problem files organized by topic. Good to review for candidate-facing prompts.
- `solutions/` : reference implementations and working solutions.

Quick evaluation checklist

- Does the code compile and run with `cargo test`?
- Are tests present and meaningful for key behaviors?
- Is ownership used correctly with no unnecessary clones?
- Is error handling explicit and ergonomic (using `Result`/`Option`)?
- Are idiomatic patterns used (iterators, pattern matching, trait bounds)?

See also: `exercises/` and `solutions/` for the curriculum and answers.
