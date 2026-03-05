This is a test dataset registry so I can become familiar with how to think about registering datasets remotely via DVC. 

https://doc.dvc.org/example-scenarios/data-registry/tutorial

in order to download you'll have to do 

```
dvc remote modify --local gdrive gdrive_client_id '$CLIENT_ID'
dvc remote modify --local gdrive gdrive_client_scret '$CLIENT_SECRET'
```
