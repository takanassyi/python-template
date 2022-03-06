# Python development template (Using Poetry)

[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)
[![python3.8.12](https://img.shields.io/badge/python-v3.8-blue)](https://www.python.org/downloads/release/python-3812/)
[![python3.9.10](https://img.shields.io/badge/python-v3.9-blue)](https://www.python.org/downloads/release/python-3910/)
[![python3.10.2](https://img.shields.io/badge/python-v3.10-blue)](https://www.python.org/downloads/release/python-3102/)

[![GitHub issues](https://img.shields.io/github/issues/takanassyi/python-template.svg)](https://github.com/takanassyi/python-template/issues)
[![GitHub forks](https://img.shields.io/github/forks/takanassyi/python-template.svg)](https://github.com/takanassyi/python-template/network)
[![GitHub stars](https://img.shields.io/github/stars/takanassyi/python-template.svg)](https://github.com/takanassyi/python-template/stargazers)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/takanassyi/python-template/pulls)

---

## Project setup & procedure memo
1.  `$poetry new {project-name}`
2.  `$cd {project-name}`
3.  `$poetry add --dev pytest@latest autopep8@latest flake8@latest tox@latest`
4.  `$pyenv local {python version}`
5.  `$python -m venv .venv`
6.  `$source .venv/bin/activate`