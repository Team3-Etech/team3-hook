pipeline {
	agent any 
		stages{
			stage('1-make a left'){
				steps{
					echo "walk.."
					sh ' cat /etc/passwd'
				}
			}
			stage('2-make a right'){
				steps{
					echo "walk..."
					sh 'uptime'
				}
			}
			stage('3-make another left'){
				steps{
					echo "walk..."
					sh 'cat /etc/passwd |grep ubuntu'
				}
			}
			stage('4-cross the street'){
				steps{
					echo "walk..."
					sh 'whoami'
				}
			}
                        stage('5-at door'){
                                steps{
                                        echo "walk..."
                                        sh 'date'
                                }
                        }
		}
}
