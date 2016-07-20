node {
step([
    $class: 'ExecuteDslScripts',
    scriptLocation: [targets: ['dslJob.groovy']],
    removedJobAction: 'DELETE',
    removedViewAction: 'DELETE',
    lookupStrategy: 'SEED_JOB',
  ])

echo ("Hello from the pipeline")
sh 'env | sort'
}
