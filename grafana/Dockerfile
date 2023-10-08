FROM grafana/grafana:latest
# https://hub.docker.com/r/grafana/grafana/tags/

COPY ./data /var/lib/grafana
COPY ./config/provisioning /etc/grafana/provisioning
COPY ./log /var/log/grafana

ENV GF_SECURITY_ADMIN_PASSWORD=admin \
    GF_SECURITY_ADMIN_USER=admin \
    GF_LOG_MODE="console file" \
    GF_ANALYTICS_REPORTING_ENABLED=false \
    GF_ANALYTICS_CHECK_FOR_UPDATES=true \
    GF_ANALYTICS_CHECK_FOR_PLUGIN_UPDATES=true \
    GF_USERS_ALLOW_SIGN_UP=false \
