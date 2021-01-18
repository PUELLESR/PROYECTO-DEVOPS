 pipeline {  
    agent any  
    options { 
        skipStagesAfterUnstable() 
    } 
    stages { 
        stage('Construir') {  
            steps {  
                sh 'ls'  
            } 
        } 
        stage('Probar'){ 
            steps { 
                sh 'ls' 
                 
            } 
        } 
        stage('Desplegar') { 
            steps { 
                sh 'ls' 
            } 
        } 
    } 
} 
