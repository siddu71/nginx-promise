FROM mikefarah/yq:4


# Copy the required files into the container
ADD deployment.yaml deployment.yaml
ADD service.yaml service.yaml
ADD execute-pipeline execute-pipeline

ENTRYPOINT ["sh", "-c", "/workdir/execute-pipeline"]

