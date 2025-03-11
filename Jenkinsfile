pipeline {
agent any
stages {
stage('Checkout') {
steps {
git credentialsId: 'credenciales-github', url:
'TU_URL_DE_REPOSITORIO_GITHUB'
}
}
stage('Construcción') {
steps {
echo 'Construyendo...'
# Aquí puedes agregar los pasos de construcción de tu
proyecto
sh 'echo "Ejecutando un script de ejemplo"'
}
}
stage('Prueba') {
steps {
echo 'Probando...'
# Aquí puedes agregar los pasos de prueba de tu proyecto
sh 'echo "Ejecutando pruebas de ejemplo"'
}
}
stage('Despliegue') {
steps {
echo 'Desplegando...'
# Aquí puedes agregar los pasos de despliegue de tu proyecto
