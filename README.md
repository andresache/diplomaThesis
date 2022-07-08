## Diploma Thesis

My Diploma Thesis is entitled "A Cloud Native Deployment of a 5G Core Network with Open Source MANO and
OpenStack". The first step in my implementation was to choose an open-source project available, which in my
case was Free5GC. After testing its functionality on a local Ubuntu virtual machine, I could start the deployment.
All Network Functions of the core network were containerized in Docker containers, then a Kubernetes cluster
was created locally and the 5G core network was moved in the cluster for a better management and
orchestration. The last step was to migrate the Kubernetes cluster in Open Source MANO and OpenStack was
used as a Virtual Infrastructure Manager.
