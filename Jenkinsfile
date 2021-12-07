node{
stage('Checkout SCM'){
git branch: 'master', url: 'https://github.com/Siddharthsid12/MultiClientFront.git'
}


stage('Install node modules'){
steps{
bat 'npm install'
}
}
stage('Build'){
steps{
bat 'npm run-script build'
}
} stage('Deploy')
{
steps{
bat 'ng serve -o'
}
}
}

