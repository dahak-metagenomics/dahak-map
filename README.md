# dahak-roadmap

Several new dahak repos have cropped up. This repo describes what each dahak repo is for.

Starting with a visual schematic:

```
+--------------------------------------------------------------------------------------+
|  AWS/The Cloud                                                                       |
|  dahak-bespin:                                                                       |
|  AWS infrastructure for testing/profiling                                            |
|                                                                                      |
|                                                                                      |
|   +---------------------------+  +----------------------------------------------+    |
|   |  Spy (AWS micro instance) |  |  Yeti (AWS beefy instance)                   |    |
|   |  dahak-spy:               |  |  dahak-yeti:                                 |    |
|   |  set up monitoring node   |  |  set up beefy node running dahak workflows   |    |
|   |                           |  |                                              |    |
|   |                           |  |                                              |    |
|   +---------------------------+  |  +----------------------------------------+  |    |
|                                  |  |  Yeti Command Line                     |  |    |
|                                  |  |  dahak-taco:                           |  |    |
|                                  |  |  command line tool for dahak workflows |  |    |
|                                  |  |                                        |  |    |
|                                  |  +----------------------------------------+  |    |
|                                  |                                              |    |
|                                  +----------------------------------------------+    |
|                                                                                      |
+--------------------------------------------------------------------------------------+
```

[dahak-roadmap](https://github.com/charlesreid1/dahak-roadmap) - you are here

[dahak-bespin](https://github.com/charlesreid1/dahak-bespin) - automate the process of creating, preparing, and running dahak workflows on AWS infrastructure (goal: enable automated testing)

[dahak-spy](https://github.com/charlesreid1/dahak-spy) - dotfiles and setup scripts for spy, a monitoring and logging node (goal: enable monitoring, profiling, and logging at scale)

[dahak-yeti](https://github.com/charlesreid1/dahak-yeti) - dotfiles and setup scripts for yeti, a beefy compute node that runs dahak workflows (goal: facilitate automation of workflows)

[dahak-taco](https://github.com/charlesreid1/dahak-taco) - command line interface for running dahak workflows (goal: provide a user-friendly interface that wraps Snakemake)
