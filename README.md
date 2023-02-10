Hidden Parameter Plugin
=======================

[![Build Status](https://ci.jenkins.io/job/Plugins/job/hidden-parameter-plugin/job/master/badge/icon)](https://ci.jenkins.io/job/Plugins/job/hidden-parameter-plugin/job/master/)
[![Jenkins Plugin](https://img.shields.io/jenkins/plugin/v/hidden-parameter.svg)](https://plugins.jenkins.io/hidden-parameter)
[![GitHub release](https://img.shields.io/github/release/jenkinsci/hidden-parameter-plugin.svg?label=changelog)](https://github.com/jenkinsci/hidden-parameter-plugin/releases/latest)
[![GitHub license](https://img.shields.io/github/license/jenkinsci/hidden-parameter-plugin)](https://github.com/jenkinsci/hidden-parameter-plugin/blob/master/LICENSE)
[![Jenkins Plugin Installs](https://img.shields.io/jenkins/plugin/i/hidden-parameter.svg?color=blue)](https://plugins.jenkins.io/hidden-parameter)

## Characteristics

1. Parameters once more, it looks bad user experience.this plugin can resolve the problem.
2. Some key parameters, once modified, can lead to the risk.these parameters,only administrator can modify,to reduce the risk.
3. Hidden parameter,only hide in the build execution, in job configuration's page can modify.
4. After the build, parameter list can display hidden parameters.


## Use case

After the plugin is installed,in job configuration's page,you can see Hidden Parameter:

![](https://github.com/jenkinsci/hidden-parameter-plugin/raw/master/images/JobConfiguration1.png)

for example,you add a hidden parameter,is called hidden_para

![](https://github.com/jenkinsci/hidden-parameter-plugin/raw/master/images/JobConfiguration2.png)

click 'Build With Parameters' link ,the parameter hidden_para of the set before, is hide,don't display in this page.

![](https://github.com/jenkinsci/hidden-parameter-plugin/raw/master/images/JobConfiguration3.png)

After the build , click 'Parameters' link, parameter list can display hidden parameters hidden_para

![](https://github.com/jenkinsci/hidden-parameter-plugin/raw/master/images/JobConfiguration4.png)
