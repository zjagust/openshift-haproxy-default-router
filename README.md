# openshift-haproxy-default-router
Default HAProxy router image for OpenShift

This is a fork of default HAProxy Router image for OpenShift Origin with updated Dockerfile
which will pull and install the latest stable version of HAProxy.

## Build Guide
Docker is required to build a usable image. Clone the repo to your local disk and before you actually execute
the image build, please check if **reload-haproxy** script is executable for user and group. To build an image, execute:

`docker build -t=haproxy-router-openshift .`

## Usage
Image like this can be uploaded to OpenShift local repository and used from there.
