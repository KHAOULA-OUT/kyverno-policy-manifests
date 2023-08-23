# Repository Manifests

This repository contains the following manifests for kyverno Kubernetes:

- `pod-with-invalid-image.yaml`: This manifest defines a Pod with an invalid image.

- `pod-with-valid-image.yaml`: This manifest defines a Pod with a valid image.

- `test-pod.yaml`: This manifest defines a test Pod for validation purposes.

- `pod-resource-policy.yaml`: This manifest defines a resource limits policy for Pods.

- `validate-container-images-policy.yaml`: This manifest defines a policy to enforce the validate-container-images policy in the first-namespace and allow Pods to be created with any image in other namespaces .

- `pod-label-policy.yaml`: This manifest defines a policy to enforce specific labels on Pods.