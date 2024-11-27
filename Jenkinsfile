node{
   stage('SCM Checkout'){
     git 'https://github.com/ra-rajesh/samplecode.git'
   }
   stage('Build') {
            echo "Building the application..."
            sh 'echo "Building the application..."'
        }

        stage('Test') {
            echo "Testing the application..."
            sh 'echo "Testing the application..."'
        }

        stage('Deploy') {
            echo "Deploying Node.js application"
        }
}
