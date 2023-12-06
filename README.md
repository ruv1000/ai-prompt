# ai-prompt

| NAME                    | PROMPT                                            | DESCRIPTION                                               | EXAMPLE                                                   |
| ----------------------- | ------------------------------------------------- | --------------------------------------------------------- | --------------------------------------------------------- |
| app.yaml                | `k ai "create manifest of pod"`                   | Basic pod manifest creation with essential configurations | [app.yaml](./yaml/app.yaml)                               |
| app-livenessProbe.yaml  | `k ai "create pod manifest with liveness probe"`  | Pod manifest with liveness probe configuration            | [app-livenessProbe.yaml](./yaml/app-livenessProbe.yaml)   |
| app-readinessProbe.yaml | `k ai "create pod manifest with readiness probe"` | Pod manifest with readiness probe configuration           | [app-readinessProbe.yaml](./yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml   | `k ai "create pod manifest with volumeMounts"`    | Pod manifest with volumeMounts configuration              | [app-volumeMounts.yaml](./yaml/app-volumeMounts.yaml)     |
| app-cronjob.yaml        | `k ai "create cron job manifest"`                 | Manifest for defining a Kubernetes CronJob                | [app-cronjob.yaml](./yaml/app-cronjob.yaml)               |
| app-job.yaml            | `k ai "create job manifest"`                      | Manifest for defining a Kubernetes Job                    | [app-job.yaml](./yaml/app-job.yaml)                       |
| app-multicontainer.yaml | `k ai "create multicontainer manifest"`           | Pod manifest with multiple containers                     | [app-multicontainer.yaml](./yaml/app-multicontainer.yaml) |
| app-resources.yaml      | `k ai "create pod manifest with resources"`       | Pod manifest with specified resource requirements         | [app-resources.yaml](./yaml/app-resources.yaml)           |
| app-secret-env.yaml     | `k ai "create pod manifest with secret env"`      | Pod manifest with environment variables from secrets      | [app-secret-env.yaml](./yaml/app-secret-env.yaml)         |
