##Helm Charts

Packages that countain K8s deployable applications
The Helm tool allows to install and define them.
Helm is the package manager (analogous to yum and apt) and Charts are packages (analogous to debs and rpms).
The home for these Charts is the Kubernetes Charts repository which provides continuous integration for pull requests, as well as automated releases of Charts in the master branch.
Repo: https://github.com/helm/charts
The stable folder hosts those applications which meet minimum requirements such as proper documentation and inclusion of only Beta or higher Kubernetes resources.
The incubator folder provides a place for charts to be submitted and iterated on until they’re ready for promotion to stable at which time they will automatically be pushed out to the default repository.