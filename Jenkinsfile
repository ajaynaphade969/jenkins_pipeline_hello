node {
    stage('build'){
        echo "building"
    }
}
node {
    stage('test'){
        echo "testing"
    }
}
stage('Get approval'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying to qa"
    }
}
stage('Get approval'){
    input "Do you really want to deploy to Production environment?"
}
node {
    stage('deploy to prod'){
        echo "deploying to prod"
    }
}
