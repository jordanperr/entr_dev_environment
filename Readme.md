# Jordan's ENTR Dev Environment



## Quickstart:

1. Dependencies:
    - [Docker Desktop](https://www.docker.com/products/docker-desktop/)
    - [Microsoft VSCode](https://code.visualstudio.com)
    - [VSCode Remote-Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) (Available through the VSCode Extension Marketplace)
2. Clone repository using VSCode, or clone it and open the folder using VSCode.
3. Download the git submodules by running `git submodule update`
4. Open the project in the dev container. VSCode may prompt you for this. If it does not, go `CMD-SHIFT-P` and then type `Reopen In Container`.

## Notes:

- You may have to modify `.devcontainer/devcontainer.json` to fit your development needs. For example, you can swap the pre-built entralliance image with your own image, or rebuild it from the Dockerfile.


