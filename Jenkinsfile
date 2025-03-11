pipeline {
agent any
stages {
stage('Checkout') {
steps {
git credentialsId: 'credenciales-github', url:
'https://github.com/pablojmcontacto/Jenkinsintegracion.git'
}
}
stage('Construcción') {
steps {
echo 'Construyendo...'
sh 'echo "Ejecutando un script de ejemplo"'
}
}
stage('Prueba') {
steps {
echo 'Probando...'
sh 'echo "Ejecutando pruebas de ejemplo"'
}
}
stage('Despliegue') {
steps {
echo 'Desplegando...'
sh 'echo "Ejecutando despliegue de ejemplo"'
}
}
}
}
