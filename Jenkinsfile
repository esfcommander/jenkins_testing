pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
		stage('Testing'){
			parallel{
				stage('Test_1') {
					steps {
						echo 'Testing..'
						sh 'echo Testing'
						sh 'echo Testing'
						sh 'echo Testing'
						sh 'echo Testing'
						sh 'echo Testing'
						sh 'echo Testing'
						sh 'echo Testing'
						sh 'echo Testing'
						sh 'echo Testing'
						sh 'echo Testing'
						sh 'echo Testing'
						sh 'echo Testing'
						sh 'echo Testing'
					}
				}
				stage('Test_2') {
					steps {
						echo 'Testing..'
					}
				}
				stage('Test_3') {
					steps {
						echo 'Testing..'
					}
				}
				stage('Test_4') {
					steps {
						echo 'Testing..'
					}
				}
			}
		}
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}