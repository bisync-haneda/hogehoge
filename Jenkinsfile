#!groovy

node('master') {
	stage ('ホスト名の表示') {
		sh 'echo `hostname`'}
	stage 'show dir'
	sh 'pwd'
	stage 'シェル実行'
	sh 'sh test.sh'
}
