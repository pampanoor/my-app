node {
   stagae('SCM Checkout'){
     git 'https://github.com/pampanoor/my-app'
   } 
   stage('Compile-Package'){
      // Get maven home path
      def mvnHome tool = name: 'maven.3', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
   }
}
