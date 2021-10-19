FROM golang:bullseye
RUN useradd -s /bin/bash -m vscode
RUN groupadd docker && usermod -aG docker vscode
COPY --from=gloursdocker/docker / /