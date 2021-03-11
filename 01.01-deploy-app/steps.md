oc new-app docker-build
----
error:  local file access failed with: stat docker-build: no such file or directory
error: unable to locate any images in image streams, templates loaded in accessible projects, template files, local docker images with name "docker-build"

Argument 'docker-build' was classified as an image, image~source, or loaded template reference.

The 'oc new-app' command will match arguments to the following types:

  1. Images tagged into image streams in the current project or the 'openshift' project
     - if you don't specify a tag, we'll add ':latest'
  2. Images in the Docker Hub, on remote registries, or on the local Docker engine
  3. Templates in the current project or the 'openshift' project
  4. Git repository URLs or local paths that point to Git repositories

--allow-missing-images can be used to point to an image that does not exist yet.

See 'oc new-app -h' for examples.



