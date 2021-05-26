# Django Helm Chart

We use this chart internally. However it's not fully documented yet nor tested in a wide range of scenarios.
If you are a helm and kubernetes expert - feel free to use this and help contribute to this repo.  

# Usage

1. Add our Helm chart repo `helm repo add glitchtip https://glitchtip.gitlab.io/glitchtip-helm-chart/`
2. Review our values.yaml. At a minimum you'll need to set DATABASE_URL and SECRET_KEY.
3. Install the chart `helm install glitchtip/glitchtip --set databaseURL=your_db --set secretKey=random_string`
