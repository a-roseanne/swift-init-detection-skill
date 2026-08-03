# Swift Init Detection Skill

A compact agent skill for reviewing Swift code and catching suspicious collection initialization patterns.

## What it checks

This skill focuses on five common problems:

1. Suspicious single-element placeholders such as `[String()]`
2. Redundant explicit generic types that are already implied by the initializer
3. Optional collections initialized to empty collections when a non-optional type is more appropriate
4. Explicit collection types paired with constructors that are redundant or mismatched
5. Optional collections that are initialized but never assigned `nil`


## Usage

You can trigger the skill with prompts such as:

- "Use the Swift Init Detection skill to review this Swift file"
- "Check this code for suspicious collection initialization patterns"
- "Review this Swift code for redundant collection types and optional misuse"

## License

This project is licensed under the MIT License.
