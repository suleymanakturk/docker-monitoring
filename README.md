Merhaba,

Bu repository cadvisor, prometheus ve grafana ile docker host üzerinde çalışan konteynarlarımızın kaynak durumlarını izlememizi sağlamaktadır. 

Cadvisor: Docker host üzerinde ki kaynak durumlarını izlemektedir.
Prometheus: Cadvisor tarafından toplanan metricleri grafanaya aktarmaktadır.
Grafana: Kaynak durumunu dashboard üzerinden izlememizi sağlamaktadır.

Grafana arayüzüne eriştikten sonra grafana marketplace tarafından sağlanan dashboardları import ederek ya da kendimiz manuel dashbord oluşturarak izlemeye başlayabiliriz. Ben aşağıdaki dashboardı import ederek kullanmaya başladım. İmport ettiğim dashboardın ekran görüntüsünü görebilirsiniz.

https://grafana.com/grafana/dashboards/19908-docker-container-monitoring-with-prometheus-and-cadvisor/


![image](https://github.com/user-attachments/assets/e891edc9-d147-44f7-b584-5a8fb3e5dff7)
