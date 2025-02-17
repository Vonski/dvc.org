# stage

A set of commands to add and list <abbr>stages</abbr>:
[add](/doc/command-reference/stage/add).

## Synopsis

```usage
usage: dvc stage [-h] [-q | -v] {add,list}  ...

positional arguments:
  COMMAND
    add         Create stage.
    list        List stages.
```

## Description

_Stages_ represent individual data processes, including their input and
resulting outputs. They can be combined to capture simple data workflows,
organize data science projects, or build detailed machine learning pipelines.

`dvc stage add` can be used to create/update stages in the `dvc.yaml` file.
Similarly, `dvc stage list` helps listing the stages present in the `dvc.yaml`
file.
