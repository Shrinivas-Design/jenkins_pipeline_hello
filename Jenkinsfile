pipeline{
	agent any
		environment{
			foo = "bar"
		}
		
		stages{
			stage("Env varibales"){
				environment{
			      Name = "Alan"
		        }
				
				steps{
					echo "Foo=${env.foo}"
					echo "Name=${env.Name}"
				
				script{
					env.Variable_testName= "any test value"
				 }
				
				echo "test_value_interactive= ${env.Variable_testName}"
				
				//withENV(["anotherway_ENV_var= anotherway"]){
				//echo "thirdway = ${env.anotherway_ENV_var}"
					}
				}
			}
		}
}
