# Pipeline Catalogs

ClusterTasks is deprecated.

We need to install cluster tasks from the catalog.

```bash

oc apply -f https://github.com/openshift-pipelines/tektoncd-catalog/raw/p/experimental/tasks/task-git-clone/0.4.1/task-git-clone.yaml -n bootstrap

```

