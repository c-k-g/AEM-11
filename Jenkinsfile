pipeline
{
    agent any
    stages
        {
            stage('Build')
            {
                steps
                {
                    withMaven(jdk: 'JAVA_HOME', maven: 'M2_HOME')
                    {
                        sh "mvn -f pom.xml clean package "
                        
                    }
                }
            }
            
        }
}
