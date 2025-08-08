# docs-automated-testing
Automated testing straight from our docs

This repo uses Spread and Runme. 

## Install Spread 

Go to the Spread repo and install Spread using go install. Installing Spread from a snap will not work in this setting.

## Dir structure 

```
├── spread.yaml
└── tests
    ├── example_tutorial
    │   ├── getting-started.md
    │   └── task.yaml
    └── hello_world
        ├── example_bash_script.sh
        ├── example_tutorial.rst
        └── task.yaml
```

## List all tests 

```
spread --list
```

## Run hello world test 

```
spread multipass:ubuntu-24.04-64:tests/hello_world
```

## Run getting started tutorial 

```
spread multipass:ubuntu-24.04-64:tests/example_tutorial
```
