pipeline {
agent any

stages {

stage('Checkout Code') {
steps {
git 'https://github.com/nasiroddin-khatib/maven-springboot-employee-api.git'
}
}

stage('Build') {
steps {
sh 'mvn compile'
}
}

stage('Test') {
steps {
sh 'mvn test'
}
}

stage('Package') {
steps {
sh 'mvn clean package'
}
}

}

}i
