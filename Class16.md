## Serverless is a cloud computing application development and execution model that enables developers to build and run application code without provisioning or managing servers or backend infrastructure.

## How can one get started with Vercel, and what are the main steps involved in deploying a serverless function using Vercel?
### On the "New Project" page, under the "Import Git Repository" section, choose the account that you'd like to link a project from.
### Find the repository in the list and select Import.
### Vercel will automatically detect the framework and any necessary build settings. However, you can also configure the Project settings at this point including the build and development settings and Environment Variables. These can also be set later.
### Press the Deploy button. Vercel will create the Project and deploy it based on the chosen configurations.

## API stands for application programming interface. In essence, an API acts as a communication layer, or as the name says, an interface, that allows different systems to talk to each other without having to understand exactly what each other does.
### all APIs function mostly the same way. You usually make a request for information or data, and the API returns a response with what you requested.

## Requests is an elegant and simple HTTP library for Python, built for human beings.
                    r = requests.get('https://api.github.com/user', auth=('user', 'pass'))
                    r.status_code
                    #200
                    r.headers['content-type']
                    #'application/json; charset=utf8'
                    r.encoding
                    #'utf-8'
                    r.text
                    #'{"type":"User"...'
                    r.json()
                    #{'private_gists': 419, 'total_private_repos': 77, ...}