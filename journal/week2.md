# Week 2 — Distributed Tracing

### 1) X-Ray

#### Instrument AWS X-Ray for Flask
![Instrument AWS X-Ray for Flask](assets/week2-xray-instrument.png)

#### Add AWS x-ray pkg to requirements
![Add AWS x-ray pkg to requirements](assets/week2-xray-add-pkg-to-requirement.png)

#### Install pip depencies
![Install pip depencies](assets/week2-install-requirements.png)

#### Add AWS x-ray config to `app.py`
![Add AWS x-ray config to app.py](assets/week2-add-xray-config-to-app.png)

#### 2) Setup AWS X-Ray Resources

#### Add `aws/json/xray.json`
![Add `aws/json/xray.json`](assets/week2-aws-json-xray.png)

#### Create flask address
![Create flask address](assets/week2-xray-create-flask-address.png)

#### Create Sampling rules
![Create Sampling rules](assets/week2-xray-create-sampling-rule.png)

#### Check the sampling rules in aws console
![Check the sampling rules in aws console](assets/week2-xray-sampling-rules-created.png)

### Add Deamon Service to Docker Compose
![Add Deamon Service to Docker Compose](assets/week2-xray-add-daemon-svc-to-docker.png)

#### Add env vars to backend-flask in `docker-compose.yml` file
![Add env vars to backend-flask in docker-compose.yml file](assets/week2-xray-add-env-for-backend-flask.png)

#### Run app and check the tracer
![Run app and check the tracer](assets/week2-xray-tracer-check.png)


### HoneyComb
#### Add honeycomb requirement in `requirements.txt`
![Add honeycomb requirement in requirements.txt](assets/week2-add-otel-honeycomb-pkg-requirement.png)

#### Install pip depencies
![Install pip depencies](assets/week2-install-requirements.png)

#### Add honeycomb config to app.py
![Add honeycomb config to app.py](assets/week2-set-honeycomb-config-to-app-file.png)

#### Set Open Telemetry config to docker compose
![Set Open Telemetry config to docker compose](assets/week2-set-otel-config-in-docker-env.png)

#### Set honeycomb env
![Set honeycomb env](assets/week2-set-honeycomb-env.png)

#### Run the app and check honeycomb dashboard
![Check honeycomb dashboard](assets/week2-honeycomb-dashboard.png)

### CloudWatch Logs

#### Add to the requirements.txt
![Add to the requirements.txt](assets/week2-cloudwatch-add-pkg-to-requirement.png)

#### Install pip depencies
![Install pip depencies](assets/week2-install-requirements.png)

#### Add Logs config to app.py
![Add Logs config to app.py](assets/week2-add-logs-config-to-app-file.png)

![Add after log to app.py](assets/week2-add-after-request-log.png)

![Add logger infor on home activities](assets/week2-add-logger-info-on-home-activities.png)

#### Set the env var in backend-flask for `docker-compose.yml`
![Install pip depencies](assets/week2-cloudwatch-set-aws-env-to-docker-compose.png)

#### Check log in log groups
![Check cruddur log groups](assets/week2-check-cruddur-log-groups.png)

![Check cruddur log groups - detail](assets/week2-check-cruddur-log-group-detail.png)


### Rollbar

#### Create a new project in Rollbar called Cruddur
![Create rollback project Cruddur](assets/week2-rollbar-create-cruddur-project.png)

#### Add rollbar pkg to requrements file
![Add rollbar pkg to requrements file](assets/week2-add-rollbar-pkg-to-requirements.png)

#### Install pip depencies
![Install pip depencies](assets/week2-install-requirements.png)

#### Set access token for rollbar
![Set access token](assets/week2-rollbar-set-env.png)

#### Add to backend-flask for docker-compose.yml
![Add to backend-flask for docker-compose.yml](assets/week2-add-rollbar-env-to-docker-compose.png)

#### Add rollbar config to app.py
![Add to backend-flask for docker-compose.yml](assets/week2-add-rollbar-config-to-app-file.png)
![Add to backend-flask for docker-compose.yml cont](assets/week2-add-rollbar-config-to-app-file-1.png)

#### Run app and check rollbar dashboard
![Check rollbar dashboard](assets/week2-check-rollbar-dashboard.png)
