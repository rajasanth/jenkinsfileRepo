@Library ('jenkins-share-library') _
node {
   checkout scm 
   config('globalconfig.yml') {
        //println "Success"
    def status = mavenBuild()
    println "${status}"
   }
}
