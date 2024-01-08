FROM mcr.microsoft.com/devcontainers/go:1-1.21-bullseye

USER vscode

RUN mkdir ~/.config/nix \
    && echo "experimental-features = nix-command flakes auto-allocate-uids configurable-impure-env" | tee -a ~/.config/nix/nix.conf
