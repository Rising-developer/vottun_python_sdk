# Vottun Python SDK

The Vottun Python SDK provides an interface for interacting with Ethereum-like blockchain networks. It allows you to deploy contracts, manage allowances, query balances, and handle transactions.
Installation

You can install the SDK either locally or globally.

## Local Installation

1.  Clone the repository:

(bash)

    git clone <repository_url>

2.  Navigate to the project directory:

(bash)

    cd vottun_python_sdk

(bash)

    pip install .


## Install the SDK globally:

(bash)

    pip install <path_to_vottun_python_sdk>

If you dont want to insta the sdk you could just place your scripts in the root folder of the sdk and import the files, like shown in the example_usage.py file.

## Usage

The SDK can be used programmatically in scripts or interactively via command line prompts.
Programmatic Usage

You can use the SDK in your Python scripts as shown in the example_usage.py file. You can use it interactively by calling the prompt methods or just pass the values to the request classes to instance a new request object via code and then call the repective methods to get the responses.
