#!groovy

node { // <1>
    stage('Build') {
        sh 'make' // <1>
        archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true // <2>
    }
    stage('Test') {
        /* .. snip .. */
    }
    stage('Deploy') {
        /* .. snip .. */
    }
    stage('Finished') {
        /* .. snip .. */
    }
}