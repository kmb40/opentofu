Installation of TOFU on a Macbook Ventura

1 - Download and Install go language from the official website.
2 - Download and Install TOFU from the official website.
3 - Clone the official opentofu repo.
4 - Use 'go build -o bin/ ./cmd/tofu' instead of 'go build .'
5 - Use 'sudo cp bin/tofu /usr/local/bin' instead of 'sudo cp opentofu /usr/local/bin'