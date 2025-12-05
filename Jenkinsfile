@Library("river-jenkins-shared-lib") _ 

appBuildAndDeployV2([
    dockerImageName: "umami",
    containerPort: "8080",
    healthCheckPath: "/actuator/health",
    buildSystem: "java"
])