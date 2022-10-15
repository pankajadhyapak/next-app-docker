
## Getting Started

run the development server:

```bash
docker build -t <tag> --target development .
docker run --rm -it --name <name> -p 3000:3000 -v ${PWD}:/app -w /app <tag>
```
Build the production version
```bash
docker build -t <tag> --target production .
```
