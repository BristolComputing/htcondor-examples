# htcondor-examples
Examples for the submission of HTCondor jobs


## Testing

### Specific node
```
condor_submit testing/simple_with_specific_machine.job -append accounting_group="group_physics.hep" -append accounting_group_user=`whoami`
```

### Singularity
```
condor_submit testing/singularity_with_specific_machine.job -append accounting_group="group_physics.hep" -append accounting_group_user=`whoami`
```
