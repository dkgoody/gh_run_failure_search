# gh_run_failure_search


## Usage: gh_run_failure_search since pattern

   Looks for a specific strings in all github workflow runs that failed

## Parameters
      since - ID of the run to start the search (and all runs after that)
              (look for it in github action url)
      pattern - string/regex for grep search

## NB!
      1. Requires gh installed and in path.
          For more info see https://github.com/cli/cli#installation

      2. Run command in repo folder


## Examples
          gh_run_failure_search 123456789 "mytest ([FA]"
          gh_run_failure_search 123456789 "missing.*CRYPTO"



