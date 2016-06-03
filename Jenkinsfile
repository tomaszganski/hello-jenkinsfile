#!groovy
node {
    Stage 'Say hello world'
    sh "echo hello worlds"

    Stage 'Sleep 5'
    sleep 5

    Stage 'Update'
    echo 'update2'
}

Stage 'Other node'
node {
  echo 'other node'
}
