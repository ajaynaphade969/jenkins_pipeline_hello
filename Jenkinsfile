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
stage('Get approval for QA Deployment'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying to qa"
    }
}
stage('Get approval for Production Deployment'){
    input "Do you really want to deploy to Production environment?"
}
node {
    stage('deploy to prod'){
        echo "deploying to prod"
    }
}
