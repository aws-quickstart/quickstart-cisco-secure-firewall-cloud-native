
---
global:
  marketplace-ami: false
  owner: quickstart-eng@amazon.com
  qsname: quickstart-cisco-firewall-asav-ravpn-on-k8s
  regions:
    - ap-northeast-1
    - ap-northeast-2
    - ap-southeast-1
    - ap-southeast-2
    - eu-central-1
    - eu-west-1
    - sa-east-1
    - us-east-1
    - us-west-1
    - us-west-2
  reporting: true

tests:
  quickstart-cisco-firewall-asav-ravpn-on-k8st1:
    parameter_input: quickstart-cisco-firewall-asav-ravpn-on-k8s-example-params1.json
    template_file: quickstart-cisco-firewall-asav-ravpn-on-k8s-example1.template
  quickstart-cisco-firewall-asav-ravpn-on-k8st2:
    parameter_input: quickstart-cisco-firewall-asav-ravpn-on-k8s-example-params2.json
    template_file: quickstart-cisco-firewall-asav-ravpn-on-k8s-example2.template