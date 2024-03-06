

echo "Tải jenkins"
docker pull  jenkins/jenkins:lts
docker save -o wifi/image/jenkins_image.tar jenkins/jenkins:lts
docker load -i wifi/image/jenkins_image.tar
echo "Xong jenkins"
