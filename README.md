# kube-ovn

export ENABLE_BAREMETAL=true

export EXTERNAL_KUBE_API_SERVER_HOST={kube-api-server-lb-fip}

export EXTERNAL_OVN_DB_IP={ovn-db-lb-fip}

bash install-new.sh
