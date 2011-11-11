# Module API Examples

This repository is an SM Framework extension set intended on giving example
usage for all Module APIs exposed to Extension Developers.

Each extension within the set contains examples for the commands provided by the
corresponding API.

In order to be able to use these examples, install this repository as an SM
Framework extension:

    sm ext install apidoc https://github.com/sm/sm_apidoc

Once you have installed the apidoc extension you can then proceed to run
examples for a specific API command run that API command prefixed with sm.

As an example, let's say that we want to know details about the 'array each'
API command call,

    sm apidoc array each

This will display the examples / tutorial for the array each api.

To see all api commands documented for 'array' api,

    sm apidoc array

For descriptions,

    sm man apidoc array

Note that the apidocs are a work in progress and not yet complete.
Currently {array,files,paths} are the most complete apidocs.

