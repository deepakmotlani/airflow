# airflow

#### Steps to create user for airflow webserver, once you run this command, you will be asked for a password
> airflow users create --username dmotlani --firstname Deepak --lastname Motlani --role Admin --email motlani.deepak@gmail.com

#### In case if dags doesnt show up on the Airflow UI, reset the db using below command
> airflow db reset

#### Start the scheduler
> nohup airflow scheduler &
