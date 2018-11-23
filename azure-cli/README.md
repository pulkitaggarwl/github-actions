# GitHub Action for the Azure CLI

The GitHub Action for [Azure CLI](https://github.com/Azure/azure-cli) wraps the Azure CLI to enable managing Azure resources inside of an Action.

To log into a Azure, we recommend using the [Azure Login](../azure-login) Action.

## Usage

```

 action "Azure Login" {
  uses = "Azure/github-actions/azure-login@master"
  env = {
    AZURE_SCRIPT_PATH = "<Relative path in your repository>"
  }
}

```


### Environment variables

One of AZURE_SCRIPT_PATH / AZURE_SCRIPT is mandatory, in case both are defined AZURE_SCRIPT_PATH gets preference.

- `AZURE_SCRIPT` – **Optional** 
- `AZURE_SCRIPT_PATH` – **Optional** 

