<h1>DevOps-Tools</h1>
<p align="justify">Creates an environment with the most common tools used by DevOps engineers. First of all install Ansible over Centos 7 and next launch tools.yaml file. The command to do it is <b>ansible-playbook tools.yaml --extra-vars "ip={ your desired IP }"</b>. Jenkins run directly over the operative system and SonarQube and Nexus 3 run over kubernetes cluster. YAML file has been created using other two GitHub repositorys, <a href="https://github.com/MartiMarch/Ansible.git">Ansible</a> and <a href="https://github.com/MartiMarch/Kubernetes.git">Kubernetes.</a></p>
<table>
  <tr>
    <th>Tool</th>
    <th>Port</th>
  </tr>
  <tr>
    <td>Jenkins</td>
    <td>8080</td>
  </tr>
  <tr>
    <td>Prometheus</td>
    <td>30001</td>
  </tr>
  <tr>
    <td>Nexus 3</td>
    <td>30002</td>
  </tr>
  <tr>
    <td>SonarQube</td>
    <td>30003</td>
  </tr>
  <tr>
    <td>Git</td>
  </tr>
  <tr>
    <td>Maven<t>
  </tr>
  <tr>
    <td>JDK 11</td>
  </tr>
  <tr>
    <td>Docker</td>
  </tr>
  <tr>
    <td>Docker Compose</td>
  </tr>
  <tr>
    <td>Helm</td>
  </tr>
  <tr>
    <td>Kubernetes</td>
  </tr>
  <tr>
    <td>kubernetes-metrics</td>  
  </tr>
</table>
