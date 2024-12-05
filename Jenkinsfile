pipeline {
	agent any
	stages{
           stage('Checkout'){
		steps {
			git 'https://github.com/bhavinprasad/exam.git'
		}
	}
	   stage('Run script') {
		steps{
			sh './time.sh'
			}
		}	
	}
}
