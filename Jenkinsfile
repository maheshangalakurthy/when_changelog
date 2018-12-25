node{
	checkout([$class: 'GitSCM',
	branches: [[name : 'orgin/master']],
	userRemoteConfigs: [[url: 'https://github.com/maheshchowdary595/when_changelog']])

def changeLogFound = false
def changeLogSets = currentBuild.changeSets
println("changeLogSets.size(): ${changeLogSets.size()}")
}
	
