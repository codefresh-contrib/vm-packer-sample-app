# Deploying to a Virtual Machine with Packer

![Google Cloud plus packer plus Codefresh](gcloud-packer-codefresh.jpg)

This is an example Virtual Machine deployment that runs in a Codefresh pipeline using [Packer](https://www.packer.io/).
More details can be found in [the documentation page](https://codefresh.io/docs/docs/yaml-examples/examples/packer-gcloud).

## Prerequisites

1. Create a [free Codefresh account](https://codefresh.io/docs/docs/getting-started/create-a-codefresh-account/)
1. Create a [Google cloud account](https://cloud.google.com/)
1. Create a [Google Service account key](https://cloud.google.com/iam/docs/creating-managing-service-account-keys)


## Create Codefresh pipeline

To use Packer with Codefresh

1. Create a new pipeline
1. Add you service account json as a variable called `SERVICE_ACCOUNT`
1. Add the [pipeline content](codefresh.yml)

That's it! Run the pipeline to see it in action.


Enjoy!

