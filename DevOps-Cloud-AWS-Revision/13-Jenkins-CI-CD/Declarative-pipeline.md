# Declarative Pipeline

Declarative pipeline is structured Jenkins syntax.

Basic structure:

```groovy
pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building'
      }
    }
  }
}
```

Mini task:

- Create pipeline with Build, Test, Deploy stages.

