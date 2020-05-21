rubyonrailsをkubernetesでdeploy

version (ruby2.6.1,rails5.2.2.1,mysql5.6)

必要なもの

クラスター作成後 gcloud compute disks create --size 200GB mysql-data

secret.ymlは個人で作成してください。

できればSOPSでの暗号化がお勧めです

後port80番にしたい場合はingress使ってください
