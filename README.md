## Sensu-Plugins-netscaler

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-netscaler.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-netscaler)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-netscaler.svg)](http://badge.fury.io/rb/sensu-plugins-netscaler)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-netscaler/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-netscaler)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-netscaler/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-netscaler)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-netscaler.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-netscaler)

## Functionality

## Files

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-netscaler -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-netscaler`

#### Bundler

Add *sensu-plugins-sensu-plugins-netscaler* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-netscaler' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-netscaler' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
