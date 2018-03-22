# taurus_simplest_example
Simple example of Taurus to generate a performance tests. 

==Requirements==
Taurus https://gettaurus.org/install/Installation/

==Run the test==
Just run the following command:

bzt script.yml load.yml criteria.yml

They are separated in order to be able to have different pipelines in a CI/CD approach, having different loads and criteria for different environments or contexts.

==See also==
For more complex scripting or options, see documentation here: https://gettaurus.org/docs/Index/
