#!groovy

//def token = "input1"
//def distribution_key = "input2"
//def message = "input3"
//def release_note = "input4"

//node('master') {
node('kakutora-slave') {
	stage ('ホスト名の表示') {
		sh 'echo `hostname`'}
	stage ('show dir') {
		sh 'pwd'}
	stage ('シェル実行') {
		sh 'sh salmon.sh ${distribution_key}'}
}

echo token
echo distribution_key
echo message
echo release_note
