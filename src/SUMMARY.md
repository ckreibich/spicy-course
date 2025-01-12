# Summary

- [Goals of this book](./goals.md)
- [Why Spicy?](./why_spicy.md)
- [Prerequisites](./prerequisites.md)

---

- [Spicy language](./language.md)
  - [Hello world](./hello_world.md)
  - [Basic types](./basic_types.md)
    - [Boolean and integers](./bool_integers.md)
    - [Optional](./optional.md)
    - [Bytes and strings](./bytes_strings.md)
    - [Collections](./collections.md)
    - [User-defined types: Enums and structs](./enums_structs.md)
    - [Exercises](./basic_types_exercises.md)
  - [Variables](./variables.md)
  - [Conditionals and loops](./conditionals_loops.md)
  - [Functions](./functions.md)
    - [Exercises](./functions_exercises.md)
  - [Modules revisited](./modules_revisited.md)

---

- [Parsing](./parsing.md)
  - [Structure of a parser](./parser_structure.md)
    - [Attributes](./parser_structure_attributes.md)
    - [Extracting data without storing it](./parser_structure_anon_skipped.md)
    - [Hooks](./parser_structure_hooks.md)
    - [Conditional parsing](./parser_structure_conditional_parsing.md)
    - [Controlling byte order](./parser_structure_byte_order.md)
  - [Parsing types](./parsing_types.md)
  - [Exercise: A naive CSV parser](./parsing_exercise_naive_csv.md)
  - [Adding additional parser state](./parser_additional_state.md)
  - [Lookahead parsing](./parsing_lookahead.md)
  - [Error recovery](./error_recovery.md)
  <!-- - [TODO: Loosely coupled parsers: sinks & filters]() -->
  <!-- - [TODO: Hooks]() -->
<!-- - [TODO: Spicy patterns]() -->

---

- [Integrating with Zeek](./zeek_integration.md)
  - [Protocol analyzers](./zeek_protocol_analyzers.md)
    - [Message and connection semantics](./zeek_message_and_connection_semantics.md)
    - [Analyzer lifecycle](./zeek_analyzer_lifecycle.md)
    - [Passing data to Zeek](./zeek_passing_data.md)
    - [Forwarding to other analyzers](./zeek_forwarding_data.md)
  - [Exercises](./zeek_protocol_analyzer_exercises.md)
<!-- - [TODO: Debugging and profiling]() -->

    <!-- TODO: type aliases -->
