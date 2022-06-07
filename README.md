This is the repo for Tekton tasks, pipelines and other required resources

kubectl apply -f workspace-resources/
kubectl apply -f tasks/
kubectl apply -f pipelines/

Note: tasks-with-input-resources folder has tasks which uses pipelineresources for workspace and these are deprecated
https://tekton.dev/docs/pipelines/resources/
