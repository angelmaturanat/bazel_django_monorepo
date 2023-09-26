
## Requirements:

- Python: 3.*
- Bazelist


## Getting Started

Firstly we must build all the projects executing this command:

```SH
$ bazel build //...
```

## Running projects

Run the "A" Django project:
```SH
bazel run projects/django_A:manage runserver
```

Run the "B" Django project:
```SH
bazel run projects/django_B:manage runserver
```