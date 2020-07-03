# AML Platform Deployment Template

[Azure Machine Learning](https://docs.microsoft.com/en-us/azure/machine-learning/overview-what-is-azure-ml) is a cloud-based environment you can use to train, deploy, automate, manage, and track machine learning models and data science workflows. This deployment template takes an [Infrastructure as Code](https://docs.microsoft.com/en-us/azure/devops/learn/what-is-infrastructure-as-code) approach with DevOps principles of [continuous integration (CI)](https://docs.microsoft.com/en-us/azure/devops/learn/what-is-continuous-integration) and [continuous delivery (CD)](https://docs.microsoft.com/en-us/azure/devops/learn/what-is-continuous-delivery).

The template contains code and DevOps pipeline definitions to automate the deployment of an [Azure Machine Learning Workspace](https://docs.microsoft.com/en-us/azure/machine-learning/concept-workspace) along with [associated resources](https://docs.microsoft.com/en-us/azure/machine-learning/concept-workspace#resources) and [Azure Kubernetes Service](https://docs.microsoft.com/en-us/azure/aks/intro-kubernetes) as in inference cluster (when deploying machine learning models as web services). Collectivley, these form the basis of a the data science platform. The deployment template also includes the creation of a [compute cluster](https://docs.microsoft.com/en-us/azure/machine-learning/concept-compute-target#azure-machine-learning-compute-managed) and [dataset](https://docs.microsoft.com/en-us/azure/machine-learning/concept-data#datasets).

## Prerequisites

- Azure subscription (contributor or owner)
- Azure DevOps project
- GitHub account

## Getting Started

Follow the instructions in the [getting started](docs/getting_started.md) doc to deploy this solution in your own Azure subscription.

Note: the dataset used in this deployment template is the [Cardiovascular Disease dataset](https://www.kaggle.com/sulianova/cardiovascular-disease-dataset) available on Kaggle.

## References

- [Azure Machine Learning documentation](https://docs.microsoft.com/en-us/azure/machine-learning/)
- [Azure Pipelines documentation](https://docs.microsoft.com/en-us/azure/devops/pipelines/)
- [Azure Machine Learning Python SDK](https://docs.microsoft.com/en-us/python/api/overview/azure/ml/?view=azure-ml-py)
- [Azure Machine Learning CLI](https://docs.microsoft.com/en-us/azure/machine-learning/reference-azure-machine-learning-cli)
