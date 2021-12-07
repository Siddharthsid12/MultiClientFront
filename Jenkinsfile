node{
stage('Checkout SCM'){
git branch: 'master', url: 'https://github.com/Siddharthsid12/MultiClientFront.git'
}

stage('Install node modules'){
bat "npm install -g @angular/cli"
}




stage('Build'){
bat "npm run-script build"
}



}
