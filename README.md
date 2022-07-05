# Airflow on Docker -Windows 10
 Airflow on Docker - Windows 10 Kurulumu ve Python ile CSV Dosyasını PostgreSql DB'ye Yüklemek
 
 Program giriş seviye eğitim içeriği olduğundan dolayı Airflow orjinal yml dosyası sadeleştirilmiştir. Aşağıda yml dosyasından kaldırılan araç isimleri yazmaktadır.
 			
* redis:latest 
* airflow-worker 
* flower

Bu araçların dışında "LOAD_EXAMPLES" özelliği false edilerek örnek airflow Dag'larının yüklenmesi engellenmiştir. Örnek Dag'ları içe aktarmak için yml dosyasındaki AIRFLOW__CORE__LOAD_EXAMPLES: '' özelliği 'true' olmalıdır.
				
Dilerseniz güncel yml dosyasını airflow'un kendi web adresinden alabilirsiniz: https://airflow.apache.org/docs/apache-airflow/stable/start/docker.html
