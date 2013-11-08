# Puppet-skel [![Build Status](https://travis-ci.org/sbadia/puppet-skel.png?branch=master)](https://travis-ci.org/sbadia/puppet-skel)

Just a puppet-module skeleton

#### Table of contents

1. [Overview](#overview)
2. [Module description](#module-description)
3. [Parameters](#parameters)
4. [Usage](#usage)
    * [Basic usage](#basic-usage)
5. [Limitation](#limitation)
6. [Development](#development)

# Overview

Skel blablabla

A [Puppet Module](http://docs.puppetlabs.com/learning/modules1.html#modules) is a collection of related content that can be used to model the configuration of a discrete service.

# Module description

- [puppet-skel](http://forge.puppetlabs.com/sbadia/skel) on puppet forge.

## Dependencies
- [puppetlabs/puppetlabs-stdlib](https://github.com/puppetlabs/puppetlabs-stdlib) >= 4.1.0

# Parameters

* `fooboozoo`: A foo argument (default: foo)

# Usage

```
  class {
    'skel':
      fooboozoo => 'foobar',
  }
```

# Limitations

- TBF

# Development

Want to help - send a pull request.
