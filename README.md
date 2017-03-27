# BitBar Minikube GUI

This [BitBar](https://getbitbar.com) plugin provides a quick view of the status of your local [minikube](https://github.com/kubernetes/minikube) instance.

## Usage

### Requirements
You must have `kubectl` and `minikube` installed, and they must be in the `$PATH` available to `minikube.5s.sh`

### Features

1. The status bar icon reflects the minikube state. When minikube is inactive it's grayscale, when the VM is running it's in color.
1. Enable and disable addons by clicking them in the Addons menu.
1. Click the Dashboard menu item to open the Dashboard webpage in your default browser