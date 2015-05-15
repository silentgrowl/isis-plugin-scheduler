# Isis plugin: Scheduler

This plugin adds a scheduler for running time-scheduled chat commands to the [Isis chatbot](https://github.com/silentgrowl/isis)

## Installation

Copy config/scheduler.yml.example from the gem repo and save as ```config/scheduler.yml``` in your Isis installation.

Add this line to your Isis installation's Gemfile:

``ruby
gem 'isis-plugin-scheduler'
``

And then execute:

    $ bundle

## Usage

Edit the config/scheduler.yml file to define a list of plugins whose responses you wish to trigger, and when. Follow the format from the example
