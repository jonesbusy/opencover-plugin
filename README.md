# OpenCover plugin

![Build](https://ci.jenkins.io/job/Plugins/job/opencover-plugin/job/main/badge/icon)
![Contributors](https://img.shields.io/github/contributors/jenkinsci/opencover-plugin.svg?color=blue)
[![GitHub release](https://img.shields.io/github/release/jenkinsci/opencover-plugin.svg?label=changelog)](https://github.com/jenkinsci/opencover-plugin/releases/latest)
[![Jenkins Plugin Installs](https://img.shields.io/jenkins/plugin/i/opencover.svg?color=blue)](https://plugins.jenkins.io/opencover)
[![GitHub license](https://img.shields.io/github/license/jenkinsci/opencover-plugin)](https://github.com/jenkinsci/opencover-plugin/blob/main/LICENSE.md)

With this plugin you can publish your OpenCover coverage reports into Jenkins. It implements [code-coverage-api-plugin](https://github.com/jenkinsci/code-coverage-api-plugin) and can generate coverage chart, fail builds using some threshold and show diff between your pull requests and target branches.

# Usage

```publishCoverage adapters: [opencoverAdapter(mergeToOneReport: true, path: 'testing*.xml')], sourceFileResolver: sourceFiles('NEVER_STORE')```

To get better how-to information please refer to [this](https://github.com/jenkinsci/code-coverage-api-plugin#how-to-use-it) article.

## Contributing

[CONTRIBUTING](https://github.com/jenkinsci/.github/blob/master/CONTRIBUTING.md) file and make sure it is appropriate for your plugin, if not then add your own one adapted from the base file

Refer to our [contribution guidelines](https://github.com/jenkinsci/.github/blob/master/CONTRIBUTING.md)

## LICENSE

Licensed under MIT, see [LICENSE](LICENSE.md)
