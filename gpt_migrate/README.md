[tool.poetry]
name = "gpt-migrate"
version = "0.1.0"
description = "Easily migrate your codebase from one framework or language to another."

[tool.poetry.dependencies]
python = "^3.8"
langchain = "^0.1.0"
yaspin = "^1.5.0"
openai = "^0.27.0"
tree_sitter = "^0.2.2"

[build-system]
requires = ["poetry-core>=1.0.0"]
build-backend = "poetry.core.masonry.api"
```