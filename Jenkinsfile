node {
    stage('Preparation') {
        sh 'docker rm -f samplerunning || true'
    }
    stage('Build') {
        build 'BuildSampleApp'
    }
    stage('Results') {
        build 'TestSampleApp'
    }
}