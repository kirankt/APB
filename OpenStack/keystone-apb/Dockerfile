FROM ansibleplaybookbundle/apb-base
# MAINTAINER {{ $MAINTAINER }}

LABEL "com.redhat.apb.version"="0.1.0"
LABEL "com.redhat.apb.spec"=\
"aWQ6IDY0MjJiMzQ5LWZhOTgtNDBkYS05MTI5LWQwYmQyNWM0ZTViZgpuYW1lOiBrZXlzdG9uZS1h\
cGIKaW1hZ2U6IG9zcC1hcGIva2V5c3RvbmUtYXBiCmRlc2NyaXB0aW9uOiBPcGVuU3RhY2sgS2V5\
c3RvbmUKYmluZGFibGU6IFRydWUKYXN5bmM6IG9wdGlvbmFsCnBhcmFtZXRlcnM6IFtdCg=="

COPY playbooks /opt/apb/actions
COPY roles /opt/ansible/roles
USER apb
