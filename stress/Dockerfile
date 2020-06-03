FROM registry.access.redhat.com/rhscl/httpd-24-rhel7

CMD ab -dSrk -c 50 -n 5000000000 http://${SCALE_SERVICE_HOST}:${SCALE_SERVICE_PORT}/index.php
