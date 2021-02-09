# Tiqets Airflow Community Helm Charts

## Charts
This is a for of the [charts/airflow](https://github.com/airflow-helm/charts/tree/main/charts/airflow) adpated to install airflow 2.0 and also with support for the [clean-logs](https://github.com/apache/airflow/blob/master/chart/templates/scheduler/scheduler-deployment.yaml#L174).

## Repo Usage

```sh
helm repo add airflow-stable https://tiqets.github.io/charts
helm repo update
```

## Contributing

Please refer to [CONTRIBUTING.md](https://github.com/airflow-helm/charts/tree/main/CONTRIBUTING.md) for details.
