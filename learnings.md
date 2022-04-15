# Pulumi Learnings

* a pulumi project is analogous to a GitHub repo: a single place for code
* a pulumi stack is an instance of above code, with a separate configuration such as environments (dev, prod) or regions
* Pulumi.yaml file defines the project (descriptions etc.)
* Pulumi.env.yaml contains the configurations per stack
* main.go contains is the program that defines the stacks resources
* pulumi/azure-native signifies that pulumi provides native azure integration => they have nightly builds with the latest Azure Features, so everything is available right away