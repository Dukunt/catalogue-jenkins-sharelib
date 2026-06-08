@Library('jenkins-test-sharedlibrary') _
def ConfigMap [
    project: "roboshop"
    component: "catalogue"
]

echo " Triggering shared library pipeline"

if( env.BRANCH_NAME.equalsIgnoreCase('main') ) {
    echo " its main branch"
}
else {
    testPipeline(ConfigMap)
}
