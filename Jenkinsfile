pipeline {
	agent any
	stages{
           stage('Checkout'){
		steps {
			git clone 'https://github.com/bhavinprasad/exam.git'
		}
	}
	   stage('Run script') {
		steps{
			sh './time.sh'
			}
		}	
	}
}