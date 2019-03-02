# HomeAssistant-AlexaPi-Docker
Docker image created from the upstream Home Assistant image that includes the AlexaPi library

## Why?
AlexaPi is required by the custom [Alexa media player component](https://github.com/keatontaylor/custom_components/) in order
to operate. Baking it into the Docker image allows Home Assistant to run on Kubernetes without having to manually reinstall
the library each time a new pod is spawned.
