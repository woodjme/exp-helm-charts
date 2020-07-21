FROM amazon/aws-cli:2.0.31

ARG kubectlVer=1.18.6

# Install kubectl
RUN curl -LO https://storage.googleapis.com/kubernetes-release/release/v${kubectlVer}/bin/linux/amd64/kubectl \
  && mv kubectl /usr/local/bin \
  && chmod +x /usr/local/bin/kubectl
