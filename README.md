---
services: sql-database
platforms: python
author: lmazuel
---

# Getting Started with Azure SQL Management in Python

FIXME

**On this page**

- [Run this sample](#run)
- [What is example.py doing?](#example)
- [More information](#more-info)

<a name="run"></a>
## Run this sample

1. If you don't already have it, [install Python](https://www.python.org/downloads/).

2. We recommend using a [virtual environment](https://docs.python.org/3/tutorial/venv.html) to run this example, but it's not mandatory. You can initialize a virtual environment this way:

    ```
    pip install virtualenv
    virtualenv mytestenv
    cd mytestenv
    source bin/activate
    ```

3. Clone the repository.

    ```
    git clone https://github.com/Azure-Samples/sql-database-python-manage.git
    ```

4. Install the dependencies using pip.

    ```
    cd sql-database-python-manage
    pip install -r requirements.txt
    ```

5. Create an Azure service principal, using 
[Azure CLI](http://azure.microsoft.com/documentation/articles/resource-group-authenticate-service-principal-cli/),
[PowerShell](http://azure.microsoft.com/documentation/articles/resource-group-authenticate-service-principal/)
or [Azure Portal](http://azure.microsoft.com/documentation/articles/resource-group-create-service-principal-portal/).

6. Export these environment variables into your current shell. 

    ```
    export AZURE_TENANT_ID={your tenant id}
    export AZURE_CLIENT_ID={your client id}
    export AZURE_CLIENT_SECRET={your client secret}
    export AZURE_SUBSCRIPTION_ID={your subscription id}
    ```

7. Run the sample.

    ```
    python example.py
    ```

<a id="example"></a>
## What is example.py doing?

FIXME

<a name="more-info"></a>
## More information

- [Azure SDK for Python](http://github.com/Azure/azure-sdk-for-python) 
- [Azure SQL Documentation](https://azure.microsoft.com/services/sql-database/)
