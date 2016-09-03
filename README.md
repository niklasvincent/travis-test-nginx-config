# travis-test-nginx-config

The `test-nginx-config.sh` script will:

1. Download the appropriate nginx Ubuntu package and extract the nginx binary
2. Test the `nginx.conf` configuration using `nginx -t -c nginx.conf`
