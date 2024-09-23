# image-cache-operator
Kubernetes operator to cache images locally


# Install kubebuilder
```sh
curl -L -o kubebuilder "https://go.kubebuilder.io/dl/latest/$(go env GOOS)/$(go env GOARCH)"
chmod +x kubebuilder && sudo mv kubebuilder /usr/local/bin/
```

# Initialize the project
```
kubebuilder init --domain my.domain --repo my.domain/image-cache-operator
```

# Create API and controller
```
kubebuilder create api --group cache --version v1 --kind ImageCache
Note:

Next: implement your new API and generate the manifests (e.g. CRDs,CRs) with:
$ make manifests
```