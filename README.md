# chef-cli-vbnet-linq-simple

## Description
A vb.net using LINQ to filter
a list of integers. VB.Net is NOT
well supported on linux so the source
code could not be compiled as part of
the build so an executable was supplied.
Built by chef.

## Tech stack
- bash
- vbnet
  - Framework 4.7
- mono 6.8
- chef 15
- ruby 2.7

## Docker stack
- docker-cli
- ubuntu:20.04

## Requirements
Docker desktop must be installed and the application
being called must be linux compatiple.

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## To see help
`sudo ./install.sh -h`

## Credits
http://knowledgebasement.com/getting-started-with-chef-and-chef-solo/
