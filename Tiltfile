SOURCE_IMAGE = os.getenv("SOURCE_IMAGE", default='.') # update registry
LOCAL_PATH = os.getenv("LOCAL_PATH", default='.')
NAMESPACE = os.getenv("NAMESPACE", default='mydev-ns')
NAME = "csharp-rest-service"

k8s_custom_deploy(
  NAME,
  apply_cmd="tanzu apps workload apply -f config/workload.yaml --update-strategy replace --debug --live-update" +
            " --local-path " + LOCAL_PATH +
            " --source-image " + SOURCE_IMAGE +
            " --namespace " + NAMESPACE +
            " --build-env BP_DEBUG_ENABLED=true" +
            " --yes " +
            " -oyaml",
  delete_cmd="tanzu apps workload delete " + NAME + " --namespace " + NAMESPACE + " --yes",
  deps=['./bin'],
  container_selector='workload',
  live_update=[
    sync('./bin/Debug/net6.0', '/workspace')
  ]
)

k8s_resource(NAME, port_forwards=["8080:8080"],
            extra_pod_selectors=[{'carto.run/workload-name': 'csharp-rest-service', 'app.kubernetes.io/component': 'run'}])

allow_k8s_contexts('tap-demo') # update the context
