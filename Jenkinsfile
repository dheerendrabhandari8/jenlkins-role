job('jenkins') {
/*  
  scm {
   github('bhanukumari/jenlkins-role', 'main')
    }
  */
  scm {
  git {
    remote {
      url 'https://github.com/dheerendrabhandari8/jenlkins-role.git'
    }

    branch 'main'
  
  steps {
        wrappers {
          sshAgent('bhanu')
    
 ansiblePlaybook('jenkins.yml') {
      inventoryPath('hosts')
   // hostKeyChecking(false)
    }
  }
  }
  }
  }
}
