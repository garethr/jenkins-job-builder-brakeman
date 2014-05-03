A plugin for [Jenkins Job
Builder](http://ci.openstack.org/jenkins-job-builder/) to enable the
Jenkins [Brakeman
plugin](https://wiki.jenkins-ci.org/display/JENKINS/Brakeman+Plugin).

[![Code
Health](https://landscape.io/github/garethr/jenkins-job-builder-brakeman/master/landscape.png)](https://landscape.io/github/garethr/jenkins-job-builder-brakeman/master)

## Usage

Include the following in your job definitions.

```yaml
- publishers:
    - brakeman:
        output: file-from-brakeman-run.tabs
```

Note that the brakeman plugin and
[brakeman](http://brakemanscanner.org/) needs to be installed.

## Installation

```bash
pip install jenkins_job_builder_brakeman
```



