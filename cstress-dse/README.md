
## examples

### common case

* custom pods
* custom service
* custom yaml

```
helm install .  --set stress.contactpods=\{solrtest-datastax-dse-0,solrtest-datastax-dse-1\} --set stress.contactservice=solrtest-datastax-dse  --set-file stress.stressYaml=/Users/ryan.svihla/code/repro_dups_pages/stress.yaml
```
