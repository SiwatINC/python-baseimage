node {
  git branch: 'main', url: 'https://github.com/SiwatINC/python-baseimage'
  docker.withRegistry("https://ghcr.io/v2") {
      docker.build("-t siwatinc/python-baseimage:python2.7",'python2.7 --no-cache').push()
      docker.build("-t siwatinc/python-baseimage:python3",'python3 --no-cache').push()
  }
}
