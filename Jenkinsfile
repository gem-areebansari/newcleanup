node {
    stage('Build') {
        echo "Building..."
        dir("/var/lib/jenkins/workspace") {
          sh 'ls'
        }
        // You can add your build commands here using 'sh' or 'bat'
        // Example: sh 'mvn clean install'
    }

    stage('Test') {
        echo "Testing..."
        // Yolu can add your test commands here using 'sh' or 'bat'
        // Example: sh 'npm test'
    }

    stage('Deploy') {
        echo "Deploying..."
        // You can add your deployment commands here using 'sh' or 'bat'
        // Example: sh 'ansible-playbook deploy.yml'
    }
}
