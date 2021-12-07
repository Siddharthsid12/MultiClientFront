node{
stage('Checkout SCM'){
git branch: 'master', url: 'https://github.com/Siddharthsid12/MultiClientFront.git'
}



stage('Install node modules'){
bat "npm install -g @angular/cli"
}




stage('Build'){
bat "npm run build"
}



stage('Deploy'){
bat "npm run ng serve"
}
}
