pipeline {
	agent any
	stages {
		stage("Build Angular Web App"){
			steps {
				// nodejs(nodeJSInstallationName: 'node 14') {
                // 	sh 'npm install' // Install dependencies
       			// 	sh 'npm run build' // Build the Angular application
                // }
				// // sh 'npm install' // Install dependencies
       			// // sh 'npm run build' // Build the Angular application
				// echo 'Building The Application... 03'

				sh '''
					docker version
					docker info
					docker compose version
					curl --version
					jq --version
				'''
			}
		}
        // stage("Build Angular Docker Image"){
		// 	steps {
		// 		// sh 'docker build -t kaemaros-angular-app .'
		// 		echo 'Testing The Application...'
		// 	}
		// }
        // stage("Deploy Angular On Docker"){
		// 	steps {
		// 		// sh 'docker run -d -p 80:80 kaemaros-angular-app'
		// 		echo 'Deploying The Application...'
		// 	}
		// }
	}
}