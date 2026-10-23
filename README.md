# gke-platform-apps
Helm values for apps that run inside the GKE cluster (lab-gke).
The cluster itself is created by the gcp-automated repo.
Reinstall with: helm install <name> <repo/chart> --version <from versions.txt> -n <ns> -f <app>/values.yaml
