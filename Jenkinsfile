node { 
     
    	stage 'Stage 1' 
    		echo 'Hello there, shell scripts' 
    	stage 'Checkout' 
    		git url: 'https://github.com/praveenjirra/shell-scripts.git' 
    	stage 'permission'
                chmod +x *.sh
	stage 'Build' 
    		sh './test.sh' 
}

