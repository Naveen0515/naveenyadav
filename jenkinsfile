pipeline {
  agent any
stages {
    stage ('greeting') {
	   steps {
	         echo  'good morning'
	   }
    }
    stage ('creation of the folder')
        steps {
            sh 'cd /home/ubuntu; sudo mkdir naveen'
        }
    }
    stage ('creation of the another folder') {
        steps {
            sh 'cd /home/ubuntu; sudo mkdir yadav'
        }
    }
  } 
}  
