# Oregon Measures Ansible Role
This role is used for configuring the oregon-measures flask app with ansible on ubuntu hosts (14.10)

## Required variables
You must set the following variables in order for this play book to run
- oregon_measrues_app_user: The name of the user that will run the server (default is 'webapp').
- oregon_measrues_bin: The bin where your preferred python executable is located. Can be pointed to virtual envs (default value is null).
- oregon_measures_base_url: Base url where the root will be served (default is '/').
- oregon_measures_static_url: Static files directory (default is '/static/').
- oregon_measures_db_host: Database host (default is 'localhost').
- oregon_measures_db_port: Database port (default is '5432').
- oregon_measures_db_user: Database username (default is 'oregon_measures').
- oregon_measures_db_pass: Database password (default is null).
- oregon_measures_db_name: Database name (default is 'oregon_measures').
- oregon_measures_wsgi_port: The port that the wsgi server listens on (default is 8000)
- oregon_measures_wsgi_workers: The number workers to spawn (default is 2)
