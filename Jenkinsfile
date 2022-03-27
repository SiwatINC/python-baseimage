node {
  git branch: 'main', url: 'https://github.com/SiwatINC/python-baseimage'
  docker.withRegistry("https://ghcr.io/v2") {
      docker.build("-t siwatinc/python-baseimage:python2.7",'-f python2.7/Dockerfile',"--no-cache").push()
      docker.build("-t siwatinc/python-baseimage:python3",'-f python3/Dockerfile',"--no-cache").push()
  }
}
