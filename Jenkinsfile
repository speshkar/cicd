node{
stage('SCM Checkout')}
{
  git 'https://github.com/speshkar/cicd'
}
stage('Compile-Package')
  {
    sh 'mvn package'
  }

}
