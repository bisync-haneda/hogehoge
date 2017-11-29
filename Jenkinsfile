#!groovy

def token = "input1"
def distribution_key = "input2"
def message = "input3"
def release_note = "input4"

node('master') {
	stage ('ホスト名の表示') {
		sh 'echo `hostname`'}
	stage ('show dir') {
		sh 'pwd'}
	stage ('シェル実行') {
		sh 'sh test.sh'}
}

def envVars= job.lastBuild.properties.get("envVars")
println envVars[distribution_key]
