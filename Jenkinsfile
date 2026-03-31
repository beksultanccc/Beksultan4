pipeline { 
    agent any 
    environment { 
    stages { 
        stage('Checkout') { ... } 
        stage('Build Java App') { ... } 
        stage('Build Docker Image') { ... } 
        stage('Start Services') { ... } 
        stage('Test Redis') { ... } 
        stage('Test PostgreSQL') { ... } 
        stage('Test Client') { ... } 
        stage('Test Nginx') { ... } 
        stage('Cleanup') { ... } 
    } 
    post { 
        always { ... } 
        success { ... } 
        failure { ... } 
    } 
} 
