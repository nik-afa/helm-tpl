# Template for our Helm charts 

##### Chartmuseum https://github.com/helm/chartmuseum

##### Helm-push https://github.com/chartmuseum/helm-push/tree/main

##### Usage
Set up vars in global or project variables:
CHART_MUSEUM_USER
CHART_MUSEUM_PASSWORD
SLACK_WEBHOOK_URL

After updated templates, use git tag
```
git add .
git commit -am "comment"
git push
git tag 1.0.0
git push origin 1.0.0
```