# Multiple Mutable Borrows in Rust
This repository demonstrates a common error in Rust: attempting to have multiple mutable borrows of the same variable.  Rust's ownership system prevents this to ensure data integrity and prevent data races.

The `bug.rs` file shows the problematic code.  The `bugSolution.rs` file provides a corrected version.

This example highlights the importance of understanding Rust's borrow checker and how to work around situations that might lead to multiple mutable borrows.