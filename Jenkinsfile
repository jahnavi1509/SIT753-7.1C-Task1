pipeline {

    agent any

    stages {

        stage('Build') {
            steps {
                echo '=== BUILD ==='
                echo 'Build the code using Maven'
                echo 'Tool: Maven'
                echo 'Compile and package the application'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo '=== UNIT AND INTEGRATION TESTS ==='
                echo 'Run unit tests using JUnit'
                echo 'Run integration tests using Selenium'
                echo 'Tools: JUnit and Selenium'
            }
        }

        stage('Code Analysis') {
            steps {
                echo '=== CODE ANALYSIS ==='
                echo 'Analyse the code for quality and coding standards'
                echo 'Tool: SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo '=== SECURITY SCAN ==='
                echo 'Scan the application for security vulnerabilities'
                echo 'Tool: Snyk'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo '=== DEPLOY TO STAGING ==='
                echo 'Deploy the application to the staging environment'
                echo 'Platform: AWS EC2'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo '=== INTEGRATION TESTS ON STAGING ==='
                echo 'Run integration tests on the staging environment'
                echo 'Tool: Selenium'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo '=== DEPLOY TO PRODUCTION ==='
                echo 'Deploy the application to the production environment'
                echo 'Platform: AWS EC2'
            }
        }
    }
}
