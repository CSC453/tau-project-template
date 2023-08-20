# tau-project-template

Template for CSC 453 Projects

## Initialization

#### Fetching the submodules

After your repository is created, you need to run the following command from the repo's top-level directory to fetch the submodules:

```bash
% git submodule update --init --recursive
```

#### Generating the stub files

Projects begin with a set of files that are auto-generated.  They are generated with the following command:

```bash
% ./tau/utilities/initialize.sh
```

That script is a linux/MacOS command.

## Fetching updates

During the semester, there may be updates/corrections to the submodules.  They can be fetched using the following command:

```bash
% git submodule update --remote --recursive
```



