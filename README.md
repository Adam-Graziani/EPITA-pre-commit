# EPITA-pre-commit
A collections of pre-commit for EPITA coding style-compliant projects.

## Usage

Download the [compile_flags.txt](), [.pre-commit-config.yaml]() and [.clang-tidy-epita]() files to the root of your repository.

Run the following at the root of your terminal:
```sh
pip install pre-commit
pre-commit install
```

## Configuration
`clang-tidy` requirs information about the buid options. A default [compile_flags.txt]() file is provided, which can and should be modified. If you use a `Makefile`, a configutation file can be created automatically using `bear`.
```sh
bear -- make
```
