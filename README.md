\# Newman API Tests



Postman collection for the JSONPlaceholder comments API, run with Newman in GitHub Actions.



\## Run locally

npm install -g newman

newman run postman/comments-api.postman\_collection.json --env-var "baseUrl=https://jsonplaceholder.typicode.com"



\## CI

Runs on every push to main, on pull requests, daily at 08:00 AM IST, and on demand.

