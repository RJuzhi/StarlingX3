# StarlingX3
StarlingX3 Images

```shell
  "download_images_list": [
        "k8s.gcr.io/kube-apiserver:v1.16.2",
        "k8s.gcr.io/kube-controller-manager:v1.16.2",
        "k8s.gcr.io/kube-scheduler:v1.16.2",
        "k8s.gcr.io/kube-proxy:v1.16.2",
        "k8s.gcr.io/pause:3.1",
        "k8s.gcr.io/etcd:3.3.15-0",
        "k8s.gcr.io/coredns:1.6.2",
        "quay.io/calico/cni:v3.6.2",
        "quay.io/calico/node:v3.6.2",
        "quay.io/calico/kube-controllers:v3.6.2",
        "docker.io/starlingx/multus:v3.2.16",
        "docker.io/starlingx/k8s-cni-sriov:master-centos-stable-latest",
        "docker.io/starlingx/k8s-plugins-sriov-network-device:master-centos-stable-latest",
        "gcr.io/kubernetes-helm/tiller:v2.13.1",
        "quay.io/airshipit/armada:8a1638098f88d92bf799ef4934abe569789b885e-ubuntu_bionic"
    ]
```

```shell
  "platform": [
        docker.io/starlingx/ceph-config-helper:v1.15.0
        quay.io/kubernetes_incubator/node-feature-discovery:v0.3.0
        quay.io/external_storage/rbd-provisioner:v2.1.1-k8s1.11
    ]
```

```shell
  "openstack-1.0-19": [
        docker.io/starlingx/stx-heat:rc-3.0-centos-stable-latest
        docker.io/starlingx/stx-nova-api-proxy:rc-3.0-centos-stable-latest
        docker.io/starlingx/stx-ceilometer:rc-3.0-centos-stable-latest
        docker.io/starlingx/stx-mariadb:rc-3.0-centos-stable-latest
        docker.io/starlingx/stx-fm-rest-api:rc-3.0-centos-stable-latest
        docker.io/starlingx/stx-libvirt:rc-3.0-centos-stable-latest
        docker.io/starlingx/stx-placement:rc-3.0-centos-stable-latest
        docker.io/starlingx/stx-barbican:rc-3.0-centos-stable-latest
        docker.io/starlingx/stx-keystone:rc-3.0-centos-stable-latest
        docker.io/starlingx/stx-nova:rc-3.0-centos-stable-latest
        docker.io/starlingx/ceph-config-helper:v1.15.0
        docker.io/starlingx/stx-panko:rc-3.0-centos-stable-latest
        docker.io/openstackhelm/mariadb:10.2.18
        docker.io/starlingx/stx-aodh:rc-3.0-centos-stable-latest
        docker.io/starlingx/stx-glance:rc-3.0-centos-stable-latest
        docker.io/starlingx/stx-cinder:rc-3.0-centos-stable-latest
        docker.io/starlingx/stx-gnocchi:rc-3.0-centos-stable-latest
        docker.io/starlingx/stx-neutron:rc-3.0-centos-stable-latest
        docker.io/starlingx/stx-ironic:rc-3.0-centos-stable-latest
        docker.io/nginx:1.13.3
        docker.io/starlingx/stx-keystone-api-proxy:rc-3.0-centos-stable-latest
        docker.io/starlingx/stx-horizon:rc-3.0-centos-stable-latest
        docker.io/starlingx/stx-ovs:rc-3.0-centos-stable-latest
        docker.io/openstackhelm/heat:ocata-ubuntu_xenial
        docker.io/rabbitmq:3.7-management
        docker.io/kolla/ubuntu-source-aodh-api:ocata
        docker.io/kolla/ubuntu-source-aodh-evaluator:ocata
        docker.io/kolla/ubuntu-source-aodh-listener:ocata
        docker.io/kolla/ubuntu-source-aodh-notifier:ocata
        docker.io/kolla/ubuntu-source-aodh-base:ocata
        docker.io/docker:17.07.0
        quay.io/stackanetes/kubernetes-entrypoint:v0.3.1
        docker.io/openstackhelm/barbican:ocata-ubuntu_xenial
        docker.io/xrally/xrally-openstack:1.3.0
        docker.io/mongo:3.4.9-jessie
        docker.io/kolla/ubuntu-source-ceilometer-api:ocata
        docker.io/kolla/ubuntu-source-ceilometer-central:ocata
        docker.io/kolla/ubuntu-source-ceilometer-collector:ocata
        docker.io/kolla/ubuntu-source-ceilometer-compute:ocata
        docker.io/kolla/ubuntu-source-ceilometer-base:ocata
        docker.io/kolla/ubuntu-source-ceilometer-notification:ocata
        docker.io/openstackhelm/ceph-config-helper:latest-ubuntu_xenial
        docker.io/openstackhelm/ceph-daemon:latest-ubuntu_xenial
        docker.io/openstackhelm/heat:newton-ubuntu_xenial
        docker.io/openstackhelm/cinder:ocata-ubuntu_xenial
        docker.io/port/ceph-config-helper:v1.10.3
        docker.io/starlingx/stx-keystone:master-centos-stable-latest
        docker.io/starlingx/stx-fm-rest-api:master-centos-stable-latest
        docker.io/starlingx/stx-heat:master-centos-stable-latest
        docker.io/starlingx/stx-mariadb:master-centos-stable-latest
        docker.io/openstackhelm/glance:ocata-ubuntu_xenial
        docker.io/postgres:9.5
        quay.io/attcomdev/ubuntu-source-gnocchi-api:3.0.3
        quay.io/attcomdev/ubuntu-source-gnocchi-statsd:3.0.3
        quay.io/attcomdev/ubuntu-source-gnocchi-metricd:3.0.3
        quay.io/attcomdev/ubuntu-source-gnocchi-base:3.0.3
        docker.io/openstackhelm/horizon:ocata-ubuntu_xenial
        docker.io/openstackhelm/osh-selenium:latest-ubuntu_xenial
        docker.io/openstackhelm/neutron:ocata-ubuntu_xenial
        docker.io/osixia/keepalived:1.4.5
        quay.io/kubernetes-ingress-controller/nginx-ingress-controller:0.23.0
        docker.io/openstackhelm/ironic:ocata-ubuntu_xenial
        docker.io/openstackhelm/keystone:ocata-ubuntu_xenial
        docker.io/openstackhelm/heat:pike
        docker.io/starlingx/stx-keystone-api-proxy:master-centos-stable-latest
        docker.io/openstackhelm/libvirt:latest-ubuntu_xenial
        docker.io/openstackhelm/magnum:ocata-ubuntu_xenial
        docker.io/mariadb:10.2.13
        docker.io/prom/mysqld-exporter:v0.10.0
        docker.io/openstackhelm/mariadb:latest-ubuntu_xenial
        quay.io/kubernetes-ingress-controller/nginx-ingress-controller:0.9.0
        docker.io/memcached:1.5.5
        docker.io/prom/memcached-exporter:v0.4.1
        docker.io/openstackhelm/neutron:ocata-18.04-sriov
        docker.io/openstackhelm/nova:ocata-ubuntu_xenial
        docker.io/kolla/ubuntu-source-nova-compute-ironic:ocata
        docker.io/kolla/ubuntu-source-nova-novncproxy:ocata
        docker.io/kolla/ubuntu-source-nova-spicehtml5proxy:ocata
        docker.io/starlingx/stx-nova-api-proxy:master-centos-stable-latest
        docker.io/openstackhelm/openvswitch:latest-ubuntu_bionic
        docker.io/kolla/ubuntu-source-panko-api:ocata
        docker.io/kolla/ubuntu-source-panko-base:ocata
        docker.io/openstackhelm/placement:ocata-ubuntu_xenial
        docker.io/kbudde/rabbitmq-exporter:v0.21.0
        docker.io/rabbitmq:3.7.13
        docker.io/rabbitmq:3.7.13-management
    ]
```


```shell
  "questions": [
        docker.io/openstackhelm/placement:ocata-ubuntu_xenial not found
  ]
````
