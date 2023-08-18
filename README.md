# learn-helm
helm create oci \n
helm package oci \n
helm registry login registry-1.docker.io
helm push oci-0.1.0.tgz oci://registry-1.docker.io/skaliarman

Pull from private repo.
Here config.json is repo owner's config file
helm pull oci://registry-1.docker.io/skaliarman/oci-private --version 0.1.0 --registry-config=~/config.json





