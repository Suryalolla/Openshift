stage 'Checkout SCM'
node {
	echo "hello world"
}

stage 'Build'
node {
sh 'mvn -DskipTests clean package'
}
