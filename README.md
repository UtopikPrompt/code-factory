# code-factory

Application source for the Code Factory task orchestration system. This
repository owns the gateway, management UI/API, supervisor, worker, and the
`orchestrator` Helm chart.

- Runtime components: `orchestrator/`
- Application chart: `helm/orchestrator/`
- Infrastructure selection and deployment operations: the
	[infra-codefactory repository](https://github.com/UtopikLab/infra-codefactory)

The repository split does not itself publish artifacts, change a cluster, or
perform a deployment cutover.