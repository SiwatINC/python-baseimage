node {
  git branch: 'main', url: 'https://github.com/SiwatINC/python-baseimage'
  docker.withRegistry("https://ghcr.io/v2") {
      docker.build("siwatinc/python-baseimage:python2.7",'python2.7').push()
      docker.build("siwatinc/python-baseimage:python3",'python3').push()
  }
}
