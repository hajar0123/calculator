pipeline {
agent any
stages {
	stage("Checkout") {
		steps {
			git url: "https://github.com/hajar0123/calculator.git", branch: "main"
		}
	}
	
	stage("Compilation") {
                steps {
                        sh "./gradlew compileJava"
                }
        }
}
}
