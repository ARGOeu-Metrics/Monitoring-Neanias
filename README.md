# Monitoring Neanias

Monitoring Neanias  Infrastructure.

Monitoring URL: https://neanias.ui.devel.argo.grnet.gr/

# Service Types
The different service types currently supported are:

| A/A  | Service Type | Description |
| ------------- | ------------- |------------- |
|1|	AAI |	NEANIAS project SSO service |
|2|	JupyterHub |	Neanias project Jupyter service |
|3|	MinIO	Neanias project | Trained AI models service |
|4|	Nextcloud |	NEANIAS project Data sharing service |
|5|	WebService|	Neanias project Web service |

# Metrics 

The basics metrics are:

**_Specific ones:_** 
- **argo.keycloak.login**: Checks the keycloak functioality. Fetches access token from Keycloak token endpoint.

**_General for all services that applies:_**
 - **generic.certificate.validity**: This metric verifies the SSL certificate on a web server to make sure it is correctly installed, valid and trusted. 
 - **generic.http.connect** : This metric checks the HTTP service on the specified host. It test normal (http) and secure (https) servers  check connection times, and report on certificate expiration times.
