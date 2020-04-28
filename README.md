# concourse-getting-started

## Purpose
This repository is meant to be paired with a blog post [link pending]. It provides some useful files for getting Concourse CI installed onto Docker Desktop Kubernetes, as well as a sample pipeline. It includes three directories: install, pipelines, and test-scripts.

### install
`values.yml`: This is an abbreviated version of the full Concourse CI values.yml file which includes only the variables which may be useful for going through the blog post guide.

`expose-concourse.sh`: A small shell script to open a node port on Kubernetes and forward it to localhost.

### pipelines
`pipeline.yml`: A sample pipeline. Detailed description of what the pipeline does, and the fubction of each section are provided in the comments of the file.

`credentials.yml`: Used to define the variables created in the pipeline.yml file

### test-scripts
`unit-tests.sh`: A very rudimentary test script. Just meant to be a placeholder for more interesting tests.

`developer-tests.sh`: Even more simple. Again, just a placeholder for something more interesting, and to help explain the concept of testing.
