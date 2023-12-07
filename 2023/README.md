# PyData Global 2023

## Installation

* python packages and awscli

```sh
pip install -r requirements.txt
```

* create AWS account with this [guide](https://docs.aws.amazon.com/accounts/latest/reference/welcome-first-time-user.html)
* create credentials with this [guide](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html#Using_CreateAccessKey) and use them for the command below

```sh
aws configure
```

## Usage

You can use the notebook [dask.local.ipynb](dask.local.ipynb) also without AWS configuration.

Instead it is mandatory to create AWS account and create credentials if you want to use the notebook [dask.cloud.ipynb](dask.cloud.ipynb).
