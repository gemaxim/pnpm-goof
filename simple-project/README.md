# simple-project

This is a pnpm project with no code, but with manifest files that have vulnerable dependencies.
The goal of this repo is to showcase the pnpm test and monitor functionalities in the cli.

Run `snyk test` or `snyk monitor`.
To include dev depenendcies, use the `--dev` option.
To see the returned dependency graph, use the `--print-graph` option.

### snyk test

`snyk test` ouput

![snyk test](../images/simple-project/snyk-test.png)
![snyk test(2)](<../images/simple-project/snyk-test(2).png>)

### snyk test --print-graph

`snyk test --print-graph` ouput

![snyk test --print-graph](../images/simple-project/snyk-test-graph.png)
![snyk test --print-graph end](<../images/simple-project/snyk-test-graph(2).png>)

### snyk monitor

`snyk monitor` cli ouput

![snyk monitor cli](../images/simple-project/snyk-monitor-cli.png)

Monitored project in UI
![snyk monitor UI](../images/simple-project/snyk-monitor-ui.png)

![snyk monitor UI depGraph](../images/simple-project/snyk-monitor-ui-dep-graph.png)
