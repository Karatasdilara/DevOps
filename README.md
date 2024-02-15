Projede Kullanılan Araçlar

1.	IDE (Visual Studio Code): Projede kullanılan entegrasyon süreci, geliştiricilerin ortak bir platformda çalışmalarını sağlamak adına Visual Studio Code IDE üzerinde gerçekleştirilmiştir. Bu, kod yazımından dağıtıma kadar tüm aşamalarda birlikte çalışmayı kolaylaştırmaktadır.

2.	Git Repo (GitHub): Kodun sürdürülebilirliği ve işbirliği için Git ve GitHub kullanılmıştır. Geliştiriciler, kodlarını paylaşabilir ve üzerinde birlikte çalışabilirler. Bu da sürekli entegrasyonu destekler.

3.	Code Scan (Snyk): Güvenlik açıklarının tespiti ve düzeltilmesi amacıyla Snyk gibi Code Scan araçları kullanılmıştır. Bu, yazılımın güvenliği açısından kritik bir adımdır.

4.	Image (Docker File): Uygulama, Docker kullanılarak konteynerize edilmiştir. Docker, uygulamanın her ortamda tutarlı bir şekilde çalışmasını sağlar.

5.	Image Registry (DockerHub): Docker Image'ı, DockerHub gibi bir Image Registry'e yüklenerek paylaşılabilir ve kullanıma hazır hale getirilmiştir.

6.	Image Scan (Snyk): Docker Image üzerinde güvenlik taraması yapmak amacıyla Snyk gibi araçlar kullanılmıştır. Bu adım, dağıtılan uygulamanın güvenliğini artırmak için önemlidir.

7.	Kubernetes Cluster: Uygulama, Kubernetes Cluster üzerinde dağıtılarak konteyner orkestrasyonu sağlanmıştır. Kubernetes, ölçeklenebilir ve yönetilebilir bir altyapı sağlar.

8.	CI / CD (ArgoCD): Sürekli Entegrasyon ve Sürekli Dağıtım süreçleri ArgoCD gibi araçlarla otomatize edilmiştir. Bu, yazılımın hızlı ve güvenilir bir şekilde dağıtılmasını sağlar.

9.	Monitoring (Prometheus, Grafana): Kubernetes Cluster üzerindeki metrikleri toplamak ve izlemek amacıyla Prometheus ve Grafana kullanılmıştır. Bu, sistem performansını gözlemlemek ve olası sorunları tespit etmek için önemlidir.
