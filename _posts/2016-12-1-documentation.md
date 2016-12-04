---
layout: post
title: Documentation
---

Information regarding Official Documentation and install instructions are available online.

<!--more-->

The Official Rust programming language website is located at:

	https://www.rust-lang.org/

Official Documentation for rust is available at:

	https://rust-lang.org/en-US/documentation.html

Here, you can find several helpful resources for learning Rust, for example, the Rust Programming language book, as well as Rust By Example, a website that provides an interactive rust tutorial.

Rust has a very active developer community, and can encourage those with questions to ask on one of their many IRC Channels. Rust also has a Youtube channel where members of the Rust community as well as developers post video presentations related to the language.

### Installation

#### Windows

Download the .msi installer from
	
	https://www.rust-lang.org/en-US/downloads.html

#### Linux and Mac
In your shell, run
	
	$ curl -sSf https://static.rust-lang.org/rustup.sh | sh
	
Or download the tarball/.pkg files directly from the link
above.

## Compiling and Running

Rust files are denoted by their .rs file extension. They can be compiled into binaries using Rust's compiler, rustc as follows

	$ rustc program.rs

a binary will be created and can be run as a normal executable in the shell

	$ ./hello

## Package Manager

Cargo is Rust's Official package manager, and comes with the current stable release of Rust. 

According to Cargo's website, it "allows Rust projects to declare their various dependencies and ensure that you’ll always get a repeatable build."

To start a binary program called "program" with cargo, use the command
	
	$ cargo new program --bin

You can create libraries rather than binary programs by leaving off the --bin flag.

Cargo keeps track of changes, and is similar to GNUs make utility. To build your project, in the projects directory, run

	$ cargo build

then you can run the binary just like you would had you manually used 	rustc to compile every file.