Installation of TOFU on a Macbook Ventura

**Note:** There appears to be a brew installation avaialble - https://formulae.brew.sh/formula/opentofu

1 - Download and Install go language from the official website. Ref - https://go.dev/doc/install
2 - Download and Install TOFU from the official website. Ref - https://opentofu.org/docs/cli/install/apt/
3 - Clone the official opentofu repo.
4 - Use 'go build -o bin/ ./cmd/tofu' instead of 'go build .'
5 - Use 'sudo cp bin/tofu /usr/local/bin' instead of 'sudo cp opentofu /usr/local/bin'.
    - **Issue:** "No such directory error" 
    
    - **Resolution:** Executable filename is 'tofo' and not 'opentofu'. Location is 'bin/tofu' instead of 'opentofu'. Information on revealing path can be found at https://iboysoft-com.cdn.ampproject.org/v/s/iboysoft.com/amp/wiki/macos-usr-local-bin.html?amp_gsa=1&amp_js_v=a9&usqp=mq331AQIUAKwASCAAgM%3D#amp_tf=From%20%251%24s&aoh=16974827865883&referrer=https%3A%2F%2Fwww.google.com&ampshare=https%3A%2F%2Fiboysoft.com%2Fwiki%2Fmacos-usr-local-bin.html

Reference
- Fork Syncing - https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork
