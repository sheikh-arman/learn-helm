# learn-helm
helm create oci <br>
helm package oci <br>
helm registry login registry-1.docker.io<br>
helm push oci-0.1.0.tgz oci://registry-1.docker.io/skaliarman<br>

Pull from private repo.<br>
Here config.json is repo owner's config file<br>
helm pull oci://registry-1.docker.io/skaliarman/oci-private --version 0.1.0 --registry-config=~/config.json





