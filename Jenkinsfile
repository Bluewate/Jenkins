node {

stage('Clone') 
{
git 'https://github.com/Bluewate/Lab12.git'

}
stage('Build') 
{

sh label: '', script: 'javac HelloJava.java'

}

stage('Run') 

{

sh label: '', 'script: 'java HelloJava'

}

}  
