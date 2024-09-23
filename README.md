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