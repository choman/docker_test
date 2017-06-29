 - sudo subscription-manager register 
 - sudo subscription-manager list --available
 - sudo subscription-manager subscribe --pool=8a85f9815847b7dd01584e3c0dcb2715

# Server:
 - sudo subscription-manager repos --enable=rhel-7-server-rpms
 - sudo subscription-manager repos --enable=rhel-7-server-extras-rpms
 - sudo subscription-manager repos --enable=rhel-7-server-optional-rpms


# Workstation:
 - sudo subscription-manager repos --enable=rhel-7-workstation-rpms
 - sudo subscription-manager repos --enable=rhel-7-workstation-extras-rpms
 - sudo subscription-manager repos --enable=rhel-7-workstation-optional-rpms
