
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
note: this project for-educational-purposes-only and it have very basic code in rust as i started to learn rust just yesterday.

this is a classic beginner programming problem: a guessing game. Here’s how it works: the program will generate a random integer between 1 and 100. It will then prompt the player to enter a guess. After a guess is entered, the program will indicate whether the guess is too low or too high. If the guess is correct, the game will print a congratulatory message and exit.

while i code this project  I practiced the fundamentals and learnt about:
* `let`
* `match`
* methods
* associated functions
* using external crates
* using cargo
* handling Potential failure with the Result type

### Built With

* [Rust](https://www.rust-lang.org/)


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* Rust
  ```sh
  curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
  ```
If you have installed Rustup some time ago, chances are your Rust version is out of date. Get the latest version of Rust by running `rustup update`.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/sameh-farouk/rust_guessing_game.git
   ```
3. cd into `rust_guessing_game`:
   ```sh
   cd rust_guessing_game
   ```
4. Compile and run it in the same step using `cargo run` command:
   ```sh
   cargo run
   ```



<!-- USAGE EXAMPLES -->
## Usage

```sh
$ cargo run
   Compiling guessing_game v0.1.0 (file:///projects/guessing_game)
    Finished dev [unoptimized + debuginfo] target(s) in 4.45s
     Running `target/debug/guessing_game`
Guess the number!
The secret number is: 61
Please input your guess.
10
You guessed: 10
Too small!
Please input your guess.
99
You guessed: 99
Too big!
Please input your guess.
foo
Please input your guess.
61
You guessed: 61
You win!
```

_For more examples, please refer to the [Guessing game tutorial](https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html)_


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [The Rust Programming Language: The Book](https://doc.rust-lang.org/book/title-page.html)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/sameh-farouk-software-developer/
