#!groovy

//def distribution_key = "input2"

//node('master') {
node('kakutora-slave') {
	stage ('ホスト名の表示') {
		sh 'echo `hostname`'}
//	stage ('シェル実行') {
//		sh 'sh salmon.sh ${distribution_key}'}
	stage ('shell-test') {
		sh 'sh salmon.sh'}
}

echo distribution_key
