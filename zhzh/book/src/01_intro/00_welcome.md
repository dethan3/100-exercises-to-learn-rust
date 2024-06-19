# 欢迎

欢迎来到 **"100 个 Rust 练习"**!

本课程将通过每次练习的方式教你 Rust 的核心概念。<br>你将了解 Rust 的语法、类型系统、标准库和生态系统。

We don't assume any prior knowledge of Rust, but we assume you know at least another programming language. We also don't assume any prior knowledge of systems programming or memory management. Those topics will be covered in the course.

In other words, we'll be starting from scratch!
 You'll build up your Rust knowledge in small, manageable steps. By the end of the course, you will have solved ~100 exercises, enough to feel comfortable working on small to medium-sized Rust projects.

## Methodology

This course is based on the "learn by doing" principle.
 It has been designed to be interactive and hands-on.

[Mainmatter](https://mainmatter.com/rust-consulting/) developed this course to be delivered in a classroom setting, over 4 days: each attendee advances through the lessons at their own pace, with an experienced instructor providing guidance, answering questions and diving deeper into the topics as needed.
 If you're interested in attending one of our training sessions, or if you'd like to bring this course to your company, please [get in touch](https://mainmatter.com/contact/).

You can also follow the course on your own, but we recommend you find a friend or a mentor to help you along the way should you get stuck. You can also find solutions to all exercises in the [`solutions` branch of the GitHub repository](https://github.com/mainmatter/100-exercises-to-learn-rust/tree/solutions).

## Structure

On the left side of the screen, you can see that the course is divided into sections. Each section introduces a new concept or feature of the Rust language.
 To verify your understanding, each section is paired with an exercise that you need to solve.

You can find the exercises in the [companion GitHub repository](https://github.com/mainmatter/100-exercises-to-learn-rust).
 Before starting the course, make sure to clone the repository to your local machine:

```bash
# If you have an SSH key set up with GitHub
git clone git@github.com:mainmatter/100-exercises-to-learn-rust.git
# Otherwise, use the HTTPS URL:
#
#   git clone https://github.com/mainmatter/100-exercises-to-learn-rust.git
```

We also recommend you work on a branch, so you can easily track your progress and pull in updates from the main repository, if needed:

```bash
cd 100-exercises-to-learn-rust
git checkout -b my-solutions
```

All exercises are located in the `exercises` folder. Each exercise is structured as a Rust package. The package contains the exercise itself, instructions on what to do (in `src/lib.rs`), and a test suite to automatically verify your solution.

### `wr`, the workshop runner

To verify your solutions, we've provided a tool that will guide you through the course. It is the `wr` CLI (short for "workshop runner"). Install it with:

```bash
cargo install --locked workshop-runner
```

In a new terminal, navigate back to the top-level folder of the repository. Run the `wr` command to start the course:

```bash
wr
```

`wr` will verify the solution to the current exercise.
 Don't move on to the next section until you've solved the exercise for the current one.

> We recommend committing your solutions to Git as you progress through the course, so you can easily track your progress and "restart" from a known point if needed.

Enjoy the course!

## Author

本课程由 [Mainmatter](https://mainmatter.com/rust-consulting/) 首席工程顾问 [Luca Palmieri](https://www.lpalmieri.com/) 编写。<br> Luca 自 2018 年以来一直使用 Rust 工作，最初在 TrueLayer，然后在 AWS。<br> Luca 是[《Rust 从零到生产》](https://zero2prod.com) 一书的作者，该书是学习如何用 Rust 构建后端应用程序的首选资源。<br>他还是多种开源 Rust 项目的作者和维护者，包括[`cargo-chef`](https://github.com/LukeMathWalker/cargo-chef) 、 [Pavex](https://pavex.dev)和[`wiremock`](https://github.com/LukeMathWalker/wiremock-rs) 。
