# GitHub Spoke Extention
Extention to the baseline GitHub Spoke functionality

This extention currently packages the following new features:

## Create Tag Action
A new action in Flow Designer which can be used to create a Tag in GitHub. This is useful if you want to setup a CI/CD pipeline 
and want to ensure Tags are created as you publish new versions like the Publish function in Studio IDE does.

## Remote Table for GitHub Commits
A new remote table which will list commits to a given file from GitHub. You can use this table to add a related list to almost any 
configuration record to display its version history in GitHub.

# Disclaimer
This app will bring in an customization to the GitHub Spoke delivered in baseline. If you have already a customization of that it might cause issues. 
It is also not guaranteed this will work through all Publish / Deploy / Update Set mechanism. You are advised to use this repository as inspiration
and test it our on a (developer instance)|[https://developer.servicenow.com]. If you like it I do recommend you re-create the elements in your instance 
from scratch or at least do a thourough testing.
