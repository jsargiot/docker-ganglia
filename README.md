jsargiot/ganglia-frontend
#########################

Run the container:

    docker run -p 0.0.0.0:80:80 jsargiot/ganglia-frontend

To set a custom gmetad.conf file via the bind mount option:

    docker run -v /my/path/to/conf:/etc/ganglia jsargiot/ganglia-frontend

To set a custom gmetad.conf file via environment variable:

    docker run -e -e DEFAULT_CONFIG_FILE=/mnt/gmetad.conf jsargiot/ganglia-frontend

