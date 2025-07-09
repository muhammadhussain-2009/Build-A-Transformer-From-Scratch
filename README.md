# Build-A-Transformer-From-Scratch
Building A Decoder Only Transformer Like ChaGPT From Scratch
<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">


# BUILD-A-TRANSFORMER-FROM-SCRATCH

<em>Unleash AI Power Through Building Transformers from Scratch</em>

<!-- BADGES -->
<img src="https://img.shields.io/github/license/muhammadhussain-2009/Build-A-Transformer-From-Scratch?style=flat&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
<img src="https://img.shields.io/github/last-commit/muhammadhussain-2009/Build-A-Transformer-From-Scratch?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/muhammadhussain-2009/Build-A-Transformer-From-Scratch?style=flat&color=0080ff" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/muhammadhussain-2009/Build-A-Transformer-From-Scratch?style=flat&color=0080ff" alt="repo-language-count">

<em>Built with the tools and technologies:</em>

<img src="https://img.shields.io/badge/Markdown-000000.svg?style=flat&logo=Markdown&logoColor=white" alt="Markdown">

</div>
<br>

---

## 📄 Table of Contents

- [Overview](#-overview)
- [Getting Started](#-getting-started)
    - [Prerequisites](#-prerequisites)
    - [Installation](#-installation)
- [Features](#-features)
- [Project Structure](#-project-structure)
    - [Project Index](#-project-index)
- [Contributing](#-contributing)
- [License](#-license)

---

## ✨ Overview

Build-A-Transformer-From-Scratch is a developer-focused project that demonstrates how to construct, train, and evaluate a decoder-only transformer model tailored for sequence generation tasks. Inspired by architectures like ChatGPT, it serves as a foundational tool for understanding and experimenting with large language models.

**Why Build-A-Transformer-From-Scratch?**

This project aims to demystify transformer architectures and provide a practical framework for building scalable NLP models. The core features include:

- 🧩 **[Puzzle Piece] Building & Training:** Step-by-step implementation of transformer architecture from scratch.
- 🚀 **[Rocket] Evaluation & Optimization:** Tools for assessing model performance and fine-tuning.
- 📝 **[Memo] Focused on Decoder-Only Models:** Ideal for language modeling and sequence generation.
- 🔍 **[Magnifying Glass] Deep Understanding:** Facilitates learning and experimentation with transformer internals.
- ⚡ **[Lightning] High Performance:** Designed for scalability and efficient training.

---

## 📌 Features

|      | Component       | Details                                                                                     |
| :--- | :-------------- | :------------------------------------------------------------------------------------------ |
| ⚙️  | **Architecture**  | <ul><li>Implementing Transformer architecture from scratch</li><li>Includes multi-head self-attention, positional encoding, feed-forward layers</li></ul> |
| 🔩 | **Code Quality**  | <ul><li>Clear modular functions for each component</li><li>Consistent naming conventions</li><li>Jupyter notebooks with inline explanations</li></ul> |
| 📄 | **Documentation** | <ul><li>README with project overview and setup instructions</li><li>In-code comments explaining key algorithms</li></ul> |
| 🔌 | **Integrations**  | <ul><li>Uses Jupyter Notebook for interactive development</li><li>Markdown for documentation</li><li>License file included for open-source licensing</li></ul> |
| 🧩 | **Modularity**    | <ul><li>Separate modules for attention, feed-forward, positional encoding</li><li>Reusable functions for tensor operations</li></ul> |
| 🧪 | **Testing**       | <ul><li>Limited unit tests for core functions (e.g., attention, layer normalization)</li><li>Notebook-based demonstrations for validation</li></ul> |
| ⚡️  | **Performance**   | <ul><li>Uses NumPy for efficient matrix operations</li><li>Potential bottlenecks in large-scale training not addressed</li></ul> |
| 🛡️ | **Security**      | <ul><li>No security features implemented; typical for educational code</li></ul> |
| 📦 | **Dependencies**  | <ul><li>jupyternotebook</li><li>markdown</li><li>license</li></ul> |

---

## 📁 Project Structure

```sh
└── Build-A-Transformer-From-Scratch/
    ├── Attention Is All You Need.pdf
    ├── Decoder_Only_Transformer.ipynb
    ├── LICENSE
    └── README.md
```

---

### 📑 Project Index

<details open>
	<summary><b><code>BUILD-A-TRANSFORMER-FROM-SCRATCH/</code></b></summary>
	<!-- __root__ Submodule -->
	<details>
		<summary><b>__root__</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ __root__</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/muhammadhussain-2009/Build-A-Transformer-From-Scratch/blob/master/Decoder_Only_Transformer.ipynb'>Decoder_Only_Transformer.ipynb</a></b></td>
					<td style='padding: 8px;'>- Decoder-Only Transformer NotebookThis notebook serves as the core implementation for a decoder-only transformer model within the project<br>- It demonstrates how to build, train, and evaluate a transformer architecture optimized for sequence generation tasks<br>- By focusing solely on the decoder component, the code enables efficient modeling of language or sequential data, aligning with the overall architecture designed for scalable and high-performance sequence modeling in the broader codebase.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/muhammadhussain-2009/Build-A-Transformer-From-Scratch/blob/master/README.md'>README.md</a></b></td>
					<td style='padding: 8px;'>- Provides an overview of the project’s goal to construct a decoder-only transformer model akin to ChatGPT from scratch<br>- It highlights the purpose of the codebase in demonstrating the architecture and training process of a large language model, emphasizing its role in enabling understanding and experimentation with transformer-based natural language processing systems within the broader project structure.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/muhammadhussain-2009/Build-A-Transformer-From-Scratch/blob/master/LICENSE'>LICENSE</a></b></td>
					<td style='padding: 8px;'>- Provides the licensing terms for the project, establishing legal permissions and restrictions for software use, distribution, and modification within the overall architecture<br>- Ensures clarity on intellectual property rights, facilitating open-source collaboration while protecting the creator’s rights<br>- Serves as a foundational legal document that supports the projects open-source distribution and community engagement.</td>
				</tr>
			</table>
		</blockquote>
	</details>
</details>

---

## 🚀 Getting Started

### 📋 Prerequisites

This project requires the following dependencies:

- **Programming Language:** JupyterNotebook

### ⚙️ Installation

Build Build-A-Transformer-From-Scratch from the source and install dependencies:

1. **Clone the repository:**

    ```sh
    ❯ git clone https://github.com/muhammadhussain-2009/Build-A-Transformer-From-Scratch
    ```

2. **Navigate to the project directory:**

    ```sh
    ❯ cd Build-A-Transformer-From-Scratch
    ```

3. **Install the dependencies:**

echo 'INSERT-INSTALL-COMMAND-HERE'
---

## 🤝 Contributing

- **💬 [Join the Discussions](https://github.com/muhammadhussain-2009/Build-A-Transformer-From-Scratch/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/muhammadhussain-2009/Build-A-Transformer-From-Scratch/issues)**: Submit bugs found or log feature requests for the `Build-A-Transformer-From-Scratch` project.
- **💡 [Submit Pull Requests](https://github.com/muhammadhussain-2009/Build-A-Transformer-From-Scratch/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/muhammadhussain-2009/Build-A-Transformer-From-Scratch
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/muhammadhussain-2009/Build-A-Transformer-From-Scratch/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=muhammadhussain-2009/Build-A-Transformer-From-Scratch">
   </a>
</p>
</details>

---

## 📜 License

Build-a-transformer-from-scratch is protected under the [LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

<div align="left"><a href="#top">⬆ Return</a></div>

---
