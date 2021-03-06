# VS Code test

I created this repo to learn the basics of python development in a container with vs code.

The goal is to get this machine learning demonstration running: <https://www.tensorflow.org/tutorials/keras/classification>

## Preparation

If you are using Windows 10, first install WSL2, the Windows Subsystem for Linux. Follow [this guide](https://docs.microsoft.com/en-us/windows/wsl/install-win10).

Install [Docker Desktop](https://www.docker.com/get-started). If you are using Windows 10, follow [this guide](https://docs.docker.com/docker-for-windows/wsl/) to configure Docker to use WSL2 on the backend.

Install [VS Code](https://code.visualstudio.com/).

Within VS Code, install the [Remote-Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension.

Download and install [git](https://git-scm.com/).

## Download and deploy this project

Click the Source Control button on the left side of VS Code (the icon has three circles and a couple lines).

Then click Clone Repository. Then enter the url for this repository - <https://github.com/caseywdunn/vscodetest> .

Select Repository Location. This is the place on your computer where the files will actually go.

A few alerts will come up on the bottom right of your screen. Click `Open`, and then `Reopen in Container`.

You should now have the code on your computer, the custom VS Code settings for this project loaded, and a live container ready to the code.

## Running the code

In the VS Code explorer (the top icon on the left side of VS Code), select `classification.ipynb`. Click the `Run all cells` button on the top left of the window. This will run the analysis.

## References

Deployment:

- <https://www.youtube.com/watch?v=Uvf2FVS1F8k>

Development:

- <https://www.youtube.com/watch?v=fPtGgOJykTM&t=240s>
- <https://code.visualstudio.com/docs/remote/containers>
