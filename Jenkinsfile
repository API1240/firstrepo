pipeline {
	 agent any 
	 
	 stages {
		stage("compile") {
			steps {
				echo "Compiling"
				bat """ javac MyDate.java """
				bat """ java MyDate"""
				}
			}
			
		stage ("run") {
			steps {
				echo "Running"
				bat """ javac MyDate.java """
				bat """ java MyDate"""
				
				}
			}
			
		}
	}
