This is contains the pure-python dependencies needed to run job-runner.

It is intended for use in OpenSAFELY backends, where we can access Github but
not PyPI, simply by checking out into a directory and adding that directory to
the PYTHONPATH.

Updates are managed via the tooling in the job-runner repo, not directly in
this repo.

There are limitations to this approach:

 - it only works for pure-python dependencies
 - we can only have one version of library

As we aim to minimise external dependecies, these limitations will probably
work for now.
