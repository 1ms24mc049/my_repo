pipeline
{
	agent any
	tools{
		jdk 'jdk21'
	}
	stages
	{
		stage("Exec java file")
                {
                        steps {
                                        echo("Java file");
                                        sh 'javac Hello.java'
										sh 'java Hello'
                        }     
                }
		
	}
}
