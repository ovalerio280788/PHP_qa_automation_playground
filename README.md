# How to make the Playground to work (UNIX)
## Steps:
- Install Docker: https://docs.docker.com/engine/install/ .
- Create a new folder in your local environment and clone this repo into it.
```bash
cd <your_new_folder>
git clone https://github.com/gorillalogic/qa_automation_playground.git
```
- Run the `deploy.sh` script to start the application.
```bash
bash deploy.sh
```

# Playground Information
| Parameter 	| Value 	|
|-	|-	|
| Site UI URL 	| http://0.0.0.0:8085 	|
| Username 	| auto 	|
| Password 	| auto 	|
| Rest API Consumer key 	| ck_1d43e7f14be1899c928b3b56f1e549bd9ea20723 	|
| Rest API Consumer secret| cs_3b94c2cee20ba6379323a3f01f79f991537a71d1 |
| Swagger URL 	| http://0.0.0.0:8085/rest-api/docs  	|
| GraphQL API URL 	| http://0.0.0.0:8085/graphql 	|
| Rest API URL 	| http://0.0.0.0:8085/wp-json/wc/v3/ 	|
| GraphQL IDE 	| http://0.0.0.0:8085/wp-admin/admin.php?page=graphiql-ide  	|

# Documents, references
- Woocommerce Rest API documentation: https://woocommerce.github.io/woocommerce-rest-api-docs/#introduction 
- GraphQL documentation: http://0.0.0.0:8085/wp-admin/admin.php?page=graphiql-ide 

# That's it, have fun!!!