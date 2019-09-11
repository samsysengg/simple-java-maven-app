import groovy.json.*
node('master') {
 deleteDir()
 stage('retrieve_RC') {
  println(":::::::::::checkout scm:::::::::::::::::::::::::::::::")
  def scmInfo = checkout scm
  sh "ls"
 }

}
