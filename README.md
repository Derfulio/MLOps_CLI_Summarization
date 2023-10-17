# MLOps_CLI_Summarization
Demo Python CLI tool to summarize text using HuggingFace

## Installer TensorFlow avec pip
- [linux](https://www.tensorflow.org/?hl=fr#linux)
- [macos](https://www.tensorflow.org/?hl=fr#macos)
- [windows-native](https://www.tensorflow.org/?hl=fr#windows-native)
- [Windows wsl2](https://www.tensorflow.org/?hl=fr#windows-wsl2)
- [cpu](https://www.tensorflow.org/?hl=fr#cpu)
- [nightly](https://www.tensorflow.org/?hl=fr#nightly)

Problème rencontré lors de l'installation sous Windows wsl2: [Poetry unable to find installation candidates for Nvidia c11 dependencies](https://github.com/python-poetry/poetry/issues/6939)
Contournement: installer directement avec PIPENV dans l'environnement virtuel, situé dans:
- ~/Library/Application Support/pypoetry sous MacOS.
- ~/.local/share/pypoetry sous Linux/Unix.
- %APPDATA%\pypoetry sous Windows.
