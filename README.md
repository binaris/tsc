# Dockerized Typescript compiler

## Usage

To compile the current directory (containing `tsconfig.json`):

```bash
docker run --rm -v $(pwd):/src binaris/tsc
```
