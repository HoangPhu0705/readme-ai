<div align="right">

[![zh-CN](https://img.shields.io/badge/zh--CN-🇨🇳-white?style=plastic)](https://github.com/eli64s/readme-ai/blob/main/docs/README-zh-CN.md)
[![fr](https://img.shields.io/badge/FR-🇫🇷-white?style=plastic)](https://github.com/eli64s/readme-ai/blob/main/docs/README-fr.md)
</div>

<div align="center">
    <h1 align="center">
        <img src="https://img.icons8.com/?size=512&id=55494&format=png" width="80" />
        <img src="https://img.icons8.com/?size=512&id=kTuxVYRKeKEY&format=png" width="80" />
        <br>README-AI
    </h1>
    <h3>◦ Generate beautiful and informative <i>README</i> files</h3>
    <h3>◦ Developed with OpenAI's GPT language model APIs</h3>
    <br>
    <p align="center">
        <img src="https://img.shields.io/badge/Markdown-000000.svg?&logo=Markdown&logoColor=white" alt="Markdown" />
        <img src="https://img.shields.io/badge/OpenAI-412991.svg?&logo=OpenAI&logoColor=white" alt="OpenAI" />
        <img src="https://img.shields.io/badge/Python-3776AB.svg?&logo=Python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/Pytest-0A9EDC.svg?&logo=Pytest&logoColor=white" alt="pytest" />
        <img src="https://img.shields.io/badge/Docker-2496ED.svg?style&logo=Docker&logoColor=white" alt="Docker" />
        <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF.svg?style&logo=GitHub-Actions&logoColor=white" alt="actions" />
    </p>
    <a href="https://pypi.org/project/readmeai/">
        <img src="https://img.shields.io/pypi/v/readmeai?color=5D6D7E&logo=pypi" alt="pypi-version" />
    </a>
    <a href="https://pypi.org/project/readmeai/">
        <img src="https://img.shields.io/pypi/pyversions/readmeai?color=5D6D7E&logo=python" alt="pypi-python-version" />
    </a>
    <a href="https://pypi.org/project/readmeai/">
        <img src="https://img.shields.io/pypi/dm/readmeai?color=5D6D7E" alt="pypi-downloads" />
    </a>
    <img src="https://img.shields.io/github/license/eli64s/readme-ai?color=5D6D7E" alt="github-license" />
    <br>
</div>

---

## 📖 Table of Contents

- [📖 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [🎈 Demos](#-demos)
- [🤖 Features](#-features)
- [👩‍💻 Usage](#-usage)
  - [🛠 Installation](#-installation)
  - [⚙️ Configuration](#️-configuration)
  - [🚀 Running *README-AI*](#-running-readme-ai)
  - [🧪 Tests](#-tests)
- [🛣 Roadmap](#-roadmap)
- [📒 Changelog](#-changelog)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---

## 📍 Overview

*README-AI* is a powerful command-line tool that generates robust README.md files for your software and data projects. By simply providing a remote repository URL or path to your codebase, this tool auto-generates documentation for your entire project, leveraging the capabilities OpenAI's GPT language model APIs.

**🎯 Motivation**

Simplifies the process of writing and maintaining high-quality project documentation, enhancing developer productivity and workflow. The ultimate goal of *readme-ai* is to improve the adoption and usability of open-source software, enabling all skill levels to better understand complex codebases and easily use open-source tools.

**⚠️ Disclaimer**

This project is currently under development and has an opinionated configuration. While *readme-ai* provides an excellent starting point for documentation, its important to review all text generated by the OpenAI API to ensure it accurately represents your codebase.

---

## 🎈 Demos

***Command-Line Interface***

‣ Run <i>readme-ai</i> in your terminal via PyPI, Docker, and more!

[cli-demo](https://github.com/eli64s/readme-ai/assets/43382407/645c2336-6ea7-444c-a927-5450930c5255)

<br>

***Streamlit Community Cloud***

‣ Use *readme-ai* directly in your browser! Zero installation, zero code!

[streamlit-demo](https://github.com/eli64s/readme-ai/assets/43382407/e8260e78-b684-4e72-941c-b3046b90c452)

---

## 🤖 Features

<br>
<div>
<details>
    <summary style="display: flex; align-items: center;">
        <span style="font-size: 1.5em;"> ❶ Project Badges</span>
    </summary>
    <table>
        <tr>
            <td>
                <h4><i>Project Slogan and Badges</i></h4>
                <p>
                    ‣ A slogan to highlight your poject is generated by <a href="https://github.com/eli64s/readme-ai/blob/main/readmeai/conf/conf.toml#L56">prompting</a> OpenAI's GPT engine.
                    </p>
                <p>
                    ‣ Codebase dependencies and metadata are visualized using <a href="https://shields.io/">Shields.io</a> badges.
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <img src="https://raw.githubusercontent.com/eli64s/readme-ai/main/examples/imgs/badges.png" alt="badges" />
            </td>
        </tr>
    </table>
</details>
</div>
<br>
<div>
    <details>
        <summary style="display: flex; align-items: center;">
            <span style="font-size: 1.5em;"> ❷ Codebase Documentation</span>
        </summary>
        <table>
            <tr>
                <td colspan="2">
                    <h4><i>Directory Tree and File Summaries</i></h4>
                </td>
            </tr>
            <tr>
                <td colspan="2">
                    <p>‣ Your project's directory structure is visualized using a custom tree function.</p>
                    <p>‣ Each file in the codebase is summarized by OpenAI's <i>GPT</i> model.</p>
                </td>
            </tr>
            <tr>
                <td align="center">
                    <img src="https://raw.githubusercontent.com/eli64s/readme-ai/main/examples/imgs/repository-tree.png" alt="repository-tree" />
                </td>
                <td align="center">
                    <img src="https://raw.githubusercontent.com/eli64s/readme-ai/main/examples/imgs/code-summaries.png" alt="code-summaries" />
                </td>
            </tr>
        </table>
    </details>
</div>
<br>
<div>
    <details>
        <summary style="display: flex; align-items: center;">
            <span style="font-size: 1.5em;"></span> ❸ Overview and Features Table</span>
        </summary>
        <table>
            <tr>
                <td>
                    <h4><i>Prompted Text Generation</i></h4>
                    <p>
                        ‣ An overview paragraph and features table are generated using <a href="https://github.com/eli64s/readme-ai/blob/main/readmeai/conf/conf.toml#L31">detailed prompts</a>, embedded with project metadata.
                    </p>
                </td>
            </tr>
            <tr>
                <td>
                    <img src="https://raw.githubusercontent.com/eli64s/readme-ai/main/examples/imgs/feature-table.png" alt="feature-table" />
                </td>
            </tr>
        </table>
    </details>
</div>
<br>
<div>
    <details>
        <summary style="display: flex; align-items: center;">
            <span style="font-size: 1.5em;"> ❹ Dynamic Usage Instructions</span><br>
        </summary>
        <table>
            <tr>
                <td>
                    <h4><i>Installation, Running, and Test</i></h4>
                    <p>
                        ‣ Generates instructions for installing, running, and testing your project. Instructions are created by identifying the codebase's top language and referring to our <a href="https://github.com/eli64s/readme-ai/blob/main/readmeai/conf/language_setup.toml">language_setup.toml</a> configuration file.
                    </p>
                </td>
            </tr>
            <tr>
                <td>
                    <img src="https://raw.githubusercontent.com/eli64s/readme-ai/main/examples/imgs/usage-instructions.png" alt="usage-instructions" />
                </td>
            </tr>
        </table>
    </details>
</div>
<br>
<div>
    <details>
        <summary style="display: flex; align-items: center;">
            <span style="font-size: 1.5em;"> ❺ Contributing Guidelines and more!</span><br>
        </summary>
        <table>
            <tr>
                <td>
                    <img src="https://raw.githubusercontent.com/eli64s/readme-ai/main/examples/imgs/roadmap.png" alt="roadmap" />
                </td>
            </tr>
            <br>
            <tr>
                <td>
                    <img src="https://raw.githubusercontent.com/eli64s/readme-ai/main/examples/imgs/license.png" alt="license" />
                </td>
            </tr>
        </table>
    </details>
</div>
<br>
<div>
    <details>
        <summary style="display: flex; align-items: center;">
            <span style="font-size: 1.5em;"> ❻ Custom Templates - coming soon</span><br>
        </summary>
        <table>
            <tr>
            <td>
                <ul>
                    <li>Developing CLI option letting users select from a variety of README styles</li>
                    <li>Templates for use-cases such as data, machine learning, web development, and more!</li>
                </ul>
            </td>
            </tr>
        </table>
    </details>
</div>
<br>
<div>
    <details>
        <summary style="display: flex; align-items: center;">
            <span style="font-size: 1.5em;"> ❼ Example README Files</span><br>
        </summary>
        <table>
            <thead>
                <tr>
                    <th></th>
                    <th>Output File</th>
                    <th>Repository</th>
                    <th>Languages</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>1️⃣</td>
                    <td><a href="https://github.com/eli64s/readme-ai/blob/main/examples/readme-python.md">readme-python.md</a></td>
                    <td><a href="https://github.com/eli64s/readme-ai">readme-ai</a></td>
                    <td>Python</td>
                </tr>
                <tr>
                    <td>2️⃣</td>
                    <td><a href="https://github.com/eli64s/readme-ai/blob/main/examples/readme-typescript.md">readme-typescript.md</a></td>
                    <td><a href="https://github.com/Yuberley/ChatGPT-App-React-Native-TypeScript">chatgpt-app-react-typescript</a></td>
                    <td>TypeScript, React</td>
                </tr>
                <tr>
                    <td>3️⃣</td>
                    <td><a href="https://github.com/eli64s/readme-ai/blob/main/examples/readme-javascript.md">readme-javascript.md</a></td>
                    <td><a href="https://github.com/idosal/assistant-chat-gpt-javascript">assistant-chat-gpt-javascript</a></td>
                    <td>JavaScript, React</td>
                </tr>
                <tr>
                    <td>4️⃣</td>
                    <td><a href="https://github.com/eli64s/readme-ai/blob/main/examples/readme-kotlin.md">readme-kotlin.md</a></td>
                    <td><a href="https://github.com/rumaan/file.io-Android-Client">file.io-android-client</a></td>
                    <td>Kotlin, Java, Android</td>
                </tr>
                <tr>
                    <td>5️⃣</td>
                    <td><a href="https://github.com/eli64s/readme-ai/blob/main/examples/readme-rust-c.md">readme-rust-c.md</a></td>
                    <td><a href="https://github.com/DownWithUp/CallMon">rust-c-app</a></td>
                    <td>C, Rust</td>
                </tr>
                <tr>
                    <td>6️⃣</td>
                    <td><a href="https://github.com/eli64s/readme-ai/blob/main/examples/readme-go.md">readme-go.md</a></td>
                    <td><a href="https://github.com/olliefr/docker-gs-ping">go-docker-app</a></td>
                    <td>Go</td>
                </tr>
                <tr>
                    <td>7️⃣</td>
                    <td><a href="https://github.com/eli64s/readme-ai/blob/main/examples/readme-java.md">readme-java.md</a></td>
                    <td><a href="https://github.com/avjinder/Minimal-Todo">java-minimal-todo</a></td>
                    <td>Java</td>
                </tr>
                <tr>
                    <td>8️⃣</td>
                    <td><a href="https://github.com/eli64s/readme-ai/blob/main/examples/readme-fastapi-redis.md">readme-fastapi-redis.md</a></td>
                    <td><a href="https://github.com/FerrariDG/async-ml-inference">async-ml-inference</a></td>
                    <td>Python, FastAPI, Redis</td>
                </tr>
                <tr>
                    <td>9️⃣</td>
                    <td><a href="https://github.com/eli64s/readme-ai/blob/main/examples/readme-mlops.md">readme-mlops.md</a></td>
                    <td><a href="https://github.com/GokuMohandas/mlops-course">mlops-course</a></td>
                    <td>Python, Jupyter</td>
                </tr>
                <tr>
                    <td>🔟</td>
                    <td><a href="https://github.com/eli64s/readme-ai/blob/main/examples/readme-pyflink.md">readme-pyflink.md</a></td>
                    <td><a href="https://github.com/eli64s/flink-flow">flink-flow</a></td>
                    <td>PyFlink</td>
                </tr>
            </tbody>
        </table>
    </details>
</div>
<br>

<p align="right">
    <a href="#top"><b>🔝 Return</b></a>
</p>


---

## 👩‍💻 Usage

***Dependencies***

Please ensure you have the following dependencies installed on your system:

- *Python version 3.9 or higher*
- *Package manager (i.e. pip, conda, poetry) or Docker*
- *OpenAI API paid account and API key*

<br>

***Repository***

A remote repository URL or path to your local project's directory is needed to use *readme-ai*. The following repository types are currently supported:
- *GitHub*
- *GitLab*
- *File System*

<br>

***OpenAI API***

An OpenAI API account and API key are needed to use *readme-ai*. The steps below outline this process:

<details closed><summary>🔐 OpenAI API - Setup Instructions</summary>

1. Go to the [OpenAI website](https://platform.openai.com/).
2. Click the "Sign up for free" button.
3. Fill out the registration form with your information and agree to the terms of service.
4. Once logged in, click on the "API" tab.
5. Follow the instructions to create a new API key.
6. Copy the API key and keep it in a secure place.

</details>

<details closed><summary>⚠️ OpenAI API - Cautionary Guidelines</summary>

1. **Review Sensitive Information**: Before running the application, ensure that all content in your repository is free of sensitive information. Please note that *readme-ai* does not filter out sensitive data from the README file, and it does not modify any files in your repository.

2. **API Usage Costs**: The OpenAI API is not free, and you will be charged for each request made. Costs can accumulate rapidly, so it's essential to be aware of your usage. You can monitor your API usage and associated costs by visiting the [OpenAI API Usage Dashboard](https://platform.openai.com/account/usage).

3. **Paid Account Recommended**: Setting up a paid account with OpenAI is highly recommended to avoid potential issues. Without a payment method on file, your API usage will be restricted to base GPT-3 models. This limitation can result in less accurate README file generation and may lead to API errors due to request limits.

4. **Runtime Considerations**: README file generation typically takes less than a minute. If the process exceeds a few minutes (e.g., 3 minutes), it's advisable to terminate *readme-ai* to prevent extended processing times.

</details>

---

### 🛠 Installation

***Using Pip***

Pip is the recommended installation method for most users.

```sh
pip install --upgrade readmeai
```
<br>

***Using Docker***

Docker is recommended for users wanting to run the application in a containerized environment.

```sh
docker pull zeroxeli/readme-ai:latest
```

<br>

<details><summary><b><i>Manually Install</i></b></summary>

<br>

1️⃣ Clone the readme-ai repository.
```sh
git clone https://github.com/eli64s/readme-ai
```

2️⃣ Navigate to readme-ai directory.

```sh
cd readme-ai
```

3️⃣ Install dependencies using a method below.

***Using Bash***
```sh
bash setup/setup.sh
```

***Using Conda***
```sh
conda create -n readmeai python=3.9 -y && \
conda activate readmeai && \
pip install -r requirements.txt
```

***Using Poetry***
```sh
poetry install
```

</details>

---

### ⚙️ Configuration

<br>

***Command-Line Arguments***

To generate a *README.md* file, use the `readmeai` command in your terminal, along with the arguments below.

| Short Flag | Long Flag      | Description                                       | Status       |
|------------|----------------|---------------------------------------------------|--------------|
| `-k`       | `--api-key`    | Your OpenAI API secret key.                       | Optional     |
| `-c`       | `--encoding`    | Encodings specify how text is converted into tokens.| Optional     |
| `-e`       | `--engine`     | OpenAI GPT language model engine (gpt-3.5-turbo)  | Optional     |
| `-f`       | `--offline-mode`| Run offline without calling the OpenAI API.      | Optional     |
| `-o`       | `--output`     | The output path for your README.md file.          | Optional     |
| `-r`       | `--repository` | The URL or path to your code repository.          | Required     |
| `-t`       | `--temperature`| The temperature (randomness) of the model         | Optional     |
| `-l`       | `--language`   | The language of text written in the README file.  | Coming Soon! |
| `-s`       | `--style`      | The README template format to use. (coming soon!) | Coming Soon! |

<br>

***Custom Settings***

To customize the README file generation process, you can modify the following sections of the [configuration file:](https://github.com/eli64s/readme-ai/blob/main/readmeai/conf/conf.toml)

- [*api*](https://github.com/eli64s/readme-ai/blob/main/readmeai/conf/conf.toml#L2) - OpenAI language model API configuration settings.
- [*git*](https://github.com/eli64s/readme-ai/blob/main/readmeai/conf/conf.toml#L12) - Default git repository settings used if no repository is provided.
- [*paths*](https://github.com/eli64s/readme-ai/blob/main/readmeai/conf/conf.toml#L17) - Directory paths and files used by the *readme-ai* application.
- [*prompts*](https://github.com/eli64s/readme-ai/blob/main/readmeai/conf/conf.toml#L26) - Large language model prompts used to generate the README file.
- [*md*](https://github.com/eli64s/readme-ai/blob/main/readmeai/conf/conf.toml#L59) - Dynamic Markdown section code templates used to build the README file.

---

### 🚀 Running *README-AI*

<br>

***Using Streamlit***

Use the app directly in your browser via Streamlit Community Cloud.

- [🛸 Take me to *readme-ai* on Streamlit!](https://readmeai.streamlit.app/)

<br>

***Using Pip***

```sh
# Option 1: Run readmeai command with all required command-line arguments.
readmeai --api-key "YOUR_API_KEY" --output readme-ai.md --repository https://github.com/eli64s/readme-ai
```
```sh
# Option 2: Run readmeai command with OpenAI API key set as environment variable.
export OPENAI_API_KEY="YOUR_API_KEY"
readmeai -o readme-ai.md -r https://github.com/eli64s/readme-ai
```

<br>

***Using Docker***

```sh
# Option 1: Run Docker container with all required command-line arguments.
docker run -it \
-e OPENAI_API_KEY="YOUR_API_KEY" \
-v "$(pwd)":/app zeroxeli/readme-ai:latest \
readmeai -o readme-ai.md -r https://github.com/eli64s/readme-ai
```
```sh
# Option 2: Run Docker container with OpenAI API key set as environment variable.
export OPENAI_API_KEY="YOUR_API_KEY"
docker run -it \
-e OPENAI_API_KEY=$OPENAI_API_KEY \
-v "$(pwd)":/app zeroxeli/readme-ai:latest \
readmeai -o readme-ai.md -r https://github.com/eli64s/readme-ai
```

<br>

<details><summary><b><i>Manually Run</i></b></summary>

<br>

***Using Conda***
```sh
conda activate readmeai
export OPENAI_API_KEY="YOUR_API_KEY"
python readmeai/main.py -o readme-ai.md -r https://github.com/eli64s/readme-ai
```

<br>

***Using Poetry***
```sh
poetry shell
export OPENAI_API_KEY="YOUR_API_KEY"
poetry run python readmeai/main.py -o readme-ai.md -r https://github.com/eli64s/readme-ai
```

</details>

---

### 🧪 Tests

Execute the test suite using the command below.

```sh
bash scripts/test.sh
```

---

## 🛣 Roadmap

- [X] Publish project as a Python library via PyPI and a Docker image on Docker Hub.
  - [*PyPI - readmeai*](https://pypi.org/project/readmeai/)
  - [*Docker Hub - readme-ai*](https://hub.docker.com/repository/docker/zeroxeli/readme-ai/general)
- [X] Integrate and deploy app with Streamlit to provide a simple user-interface for using the tool.
  - [*Streamlit Community Cloud - readmeai*](https://readmeai.streamlit.app/)
- [ ] Develop GitHub Actions script to automatically update the README file when new code is pushed.
- [ ] Design README output templates for a variety of use-cases (i.e. data, web-dev, minimal, etc.)
- [ ] Add support for generating README files in any language (i.e. CN, ES, FR, JA, KO, RU).

---

## 📒 Changelog

[Changelog](https://github.com/eli64s/readme-ai/blob/main/CHANGELOG.md)

---

## 🤝 Contributing

[Contributing Guidelines](https://github.com/eli64s/readme-ai/blob/main/CONTRIBUTING.md)

---

## 📄 License

[MIT](https://github.com/eli64s/readme-ai/blob/main/LICENSE)

---

## 👏 Acknowledgments

*Badges*
  - [Shields.io](https://shields.io/)
  - [Aveek-Saha/GitHub-Profile-Badges](https://github.com/Aveek-Saha/GitHub-Profile-Badges)
  - [Ileriayo/Markdown-Badges](https://github.com/Ileriayo/markdown-badges)

<p align="right">
  <a href="#top"><b>🔝 Return </b></a>
</p>

---
