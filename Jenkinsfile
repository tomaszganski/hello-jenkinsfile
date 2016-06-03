#!groovy
node {
    stage 'Say hello world'
    sh "echo hello worlds"

    stage 'Sleep 5'
    sleep 5

    stage 'Update'
    echo 'update2'
}

stage 'Other node'
node {
  echo 'other node'
}
