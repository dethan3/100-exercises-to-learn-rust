# 欢迎

欢迎来到 **"100 个 Rust 练习"**!

本课程将通过每次练习的方式教你 Rust 的核心概念。<br>你将了解 Rust 的语法、类型系统、标准库和生态系统。

我们不需要您具备任何 Rust 的先验知识，但我们假设您至少了解另一种编程语言。我们也不要求您具备任何系统编程或内存管理的先验知识。这些主题将在本课程中介绍。

换句话说，我们将从零开始！
您将通过小而易行的步骤积累 Rust 知识。课程结束时，您将解决约 100 个练习，足以让您轻松处理中小型 Rust 项目。

## 方法

本课程基于“边做边学”的原则。
它被设计成具有交互性和可操作性。

[Mainmatter](https://mainmatter.com/rust-consulting/)开发的这门课程将在 4 天内以课堂形式授课：每位学员按照自己的节奏学习课程，由一位经验丰富的老师提供指导、回答问题并根据需要深入探讨主题。
如果您有兴趣参加我们的某个培训课程，或者希望将此课程带到您的公司，请[与我们联系](https://mainmatter.com/contact/)。

您也可以自行学习本课程，但我们建议您找一位朋友或导师来帮助您，以防您遇到困难。您还可以在[GitHub 存储库的`solutions`分支](https://github.com/mainmatter/100-exercises-to-learn-rust/tree/solutions)中找到所有练习的解决方案。

## 结构

在屏幕左侧，你可以看到课程分为几个部分。每个部分介绍 Rust 语言的一个新概念或特性。
为了验证您的理解，每个部分都配有一个您需要解决的练习。

您可以在[配套的 GitHub 存储库](https://github.com/mainmatter/100-exercises-to-learn-rust)中找到这些练习。
在开始课程之前，请确保将存储库克隆到本地机器：

```bash
# If you have an SSH key set up with GitHub
git clone git@github.com:mainmatter/100-exercises-to-learn-rust.git
# Otherwise, use the HTTPS URL:
#
#   git clone https://github.com/mainmatter/100-exercises-to-learn-rust.git
```

我们还建议您在分支上工作，这样您就可以轻松跟踪进度并在需要时从主存储库中提取更新：

```bash
cd 100-exercises-to-learn-rust
git checkout -b my-solutions
```

所有练习都位于`exercises`文件夹中。每个练习都以 Rust 包的形式构建。该包包含练习本身、操作说明（在`src/lib.rs`中）以及用于自动验证解决方案的测试套件。

### `wr` ，车间负责人

为了验证您的解决方案，我们提供了一个工具来指导您完成本课程。它是`wr` CLI（“workshop runner”的缩写）。使用以下命令安装它：

```bash
cargo install --locked workshop-runner
```

在新终端中，导航回存储库的顶级文件夹。运行`wr`命令以启动课程：

```bash
wr
```

`wr`将验证当前练习的解决方案。
在解决当前练习之前，不要进入下一部分。

> 我们建议您在学习课程的过程中将您的解决方案提交给 Git，这样您就可以轻松跟踪您的进度并在需要时从已知点“重新启动”。

享受课程吧！

## 作者

本课程由 [Mainmatter](https://mainmatter.com/rust-consulting/) 首席工程顾问 [Luca Palmieri](https://www.lpalmieri.com/) 编写。<br> Luca 自 2018 年以来一直使用 Rust 工作，最初在 TrueLayer，然后在 AWS。<br> Luca 是[《Rust 从零到生产》](https://zero2prod.com) 一书的作者，该书是学习如何用 Rust 构建后端应用程序的首选资源。<br>他还是多种开源 Rust 项目的作者和维护者，包括[`cargo-chef`](https://github.com/LukeMathWalker/cargo-chef) 、 [Pavex](https://pavex.dev)和[`wiremock`](https://github.com/LukeMathWalker/wiremock-rs) 。
