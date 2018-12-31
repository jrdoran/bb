https://realpython.com/flask-by-example-part-1-project-setup/



https://realpython.com/flask-by-example-part-2-postgres-sqlalchemy-and-alembic/

https://realpython.com/flask-by-example-part-3-text-processing-with-requests-beautifulsoup-nltk/

https://realpython.com/flask-by-example-implementing-a-redis-task-queue/

https://realpython.com/flask-by-example-integrating-flask-and-angularjs/

https://realpython.com/updating-the-staging-environment/

https://realpython.com/flask-by-example-updating-the-ui/

https://realpython.com/flask-by-example-custom-angular-directive-with-d3/



A simple Hello World app written in Python Flask.

Contains Dockerfiles for Development (with Hot Reloading) and Production.

Build and run using any dockerfile:

```
$ docker build -f [dockerfile] -t python-docker .
$ docker run --rm -it -p 8080:8080 python-docker
```

Uses gunicorn for production build.