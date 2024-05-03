# flowair

* conda create -n starenv airflow

* export AIRFLOW_HOME=.
* airflow db init
* dags_folder = /Users/Shared/Code/OpenSource/FireShadow/Project/flowair/dags
* sql_alchemy_conn = sqlite:////Users/Shared/Code/OpenSource/FireShadow/Project/flowair/airflow.db
* airflow db reset
* airflow scheduler
* airflow webserver -p 8080
* airflow users create \
          --username admin \
          --firstname firstname \
          --lastname lastname \
          --password admin \
          --role Admin \
          --email email@email.com
