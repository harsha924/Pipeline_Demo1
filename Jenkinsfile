node {
step([
    $class: 'ExecuteDslScripts',
    scriptLocation: [scriptText: 'job("CICD_Master")'],
    removedJobAction: 'DELETE',
    removedViewAction: 'DELETE',
    lookupStrategy: 'SEED_JOB',
  ])

echo ("Hello from the pipeline")
sh 'env | sort'
}
