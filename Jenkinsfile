library identifier: 'jenkins-universal-base@master', retriever: modernSCM([
    $class: 'GitSCMSource',
    remote: 'https://github.com/gl-pipelines/jenkins-universal-base.git'
])

universalBasePipeline {
    workspaceConfigURL = "https://github.com/gsalgadoartola/demo-app.git"
    jenkinsJNLPAgentImage = "quay.io/gsalgadoartola/jenkins-jnlp-slave:3.29"
    pipelineType = "service"
    applicationName = "demo-app"
    applicationType = "golang@master"
    baseImage = "registry.access.redhat.com/ubi8/ubi-minimal"
    imageBuilderURL = "https://github.com/gl-container-images/app-golang.git"
    imageBuilderVersion = "master"
    golangImage = "quay.io/gsalgadoartola/golang:1.12.12-1"
    containerToolsImage = "quay.io/gsalgadoartola/container-tools:1.0"
    infraURL = "https://github.com/gsalgadoartola/demo-infra.git"
}
