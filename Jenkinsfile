node {
step([
    $class: 'ExecuteDslScripts',
    scriptLocation: [scriptText: 'job("name 'CICD_Master' description 'Demo Build job'")'],
    removedJobAction: 'DELETE',
    removedViewAction: 'DELETE',
    lookupStrategy: 'SEED_JOB',
  ])

echo ("Hello from the pipeline")
sh 'env | sort'
}
