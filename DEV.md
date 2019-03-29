export GITHUB_TOKEN=5f7cb5c83d7cc7264b4797c67e8c5c4dff89d0b7

labeler scan ./Repo-labels/alameda.yaml --repo containers-ai/alameda
labeler scan ./Repo-labels/alameda-api.yaml --repo containers-ai/api
labeler scan ./Repo-labels/federatorai-operator.yaml --repo containers-ai/federatorai-operator

labeler scan ./Repo-labels/alameda-ai.yaml --repo prophetstor-ai/alameda-ai
labeler scan ./Repo-labels/alameda-recommendation.yaml --repo prophetstor-ai/federatorai-recommendation