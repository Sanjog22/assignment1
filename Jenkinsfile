pipeline {
			agent {
				label 'built-in'
				}
			stages {
			
			stage ('master') {
			
			steps {
			
				sh "yum install httpd -y"
				sh "service httpd start"
				sh "cp -r /mnt/ass1/index.html /var/www/html/"
				sh "chmod -R 777 /var/www/html/index.html"
			
			}
			
			
			}
			
			
			}

}
