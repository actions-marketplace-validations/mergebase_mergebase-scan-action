# mergebase-scan-action

[![MergeBase](https://mergebase.com/wp-content/uploads/2020/10/logo.png)](https://mergebase.com)

## Description
A Github action to scan your repositories with MergeBase. Supports Java w/ Maven, NPM, .NET, Ruby, and more. 

## Required Parameters:
- project_name: name of your project in the MergeBase dashboard
- mb_url: URL of your MergeBase dashboard in the form https://[domain].mergebase.com 
- mb_token: your customer token which can be found in the settings menu of your dashboard. 

## Optional Parameters:
- additional_args: a string of any additional command line arguments to pass to the CLI. A full list can be found in our user guide. 
