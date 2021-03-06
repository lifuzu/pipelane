# Pipelane

Pipelane is a client side of continuous integration/build system on top of REST api. Pipelane will integrate existing systems as many as possible, such as JIRA, Jenkins, etc.

### How to install
```
$ pip install pipelane
```

### Then use it with appending shell commands
```
$ pipelane echo 'Hello World!'
```


### Actions

timestep (ts) - to time the build step;
systemsnap (ss) - to snapshot the system info (cpu, mem, path, os, etc.);
dependencymap (dm) - to record the dependencies with their version;

### Subsystems

Storage - store files/artifacts, as an adapter to Nexus / Artifactory;
Ticket - create Epic/story/tasks, add comments; interact with human, e.g. waiting for a decision;
Document - change logs, store links, aggregate the related information;
Log - store, analyse, search logs;
Pod - remote resource for build;
Notification - chatbot or other systems on top of Hipchat or Slack to receive notifications, send commands;
UI - simple UI to collect, simplify inputs;
Repo - interact with repo server, checkin, checkout, create branches, merge branches, review change, etc.;

### Supportive systems

Webhook
CI/System
Github/Gitlab/Gerrit
Storage servers, such as Nexus, Artifactory



[Github-flavored Markdown](https://guides.github.com/features/mastering-markdown/)


