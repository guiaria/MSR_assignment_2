*This is a reproduction project as part of the MSR course 2021/22 at UniKo, CS department, SoftLang Team*

*This repositories fork from https://github.com/gorjatschev/applying-apis for MSR 2021/22 Coursework*

# Team
Team: Mike
* Prayuth Patumcharoenpol
* Jorge Gavilan

# Baseline study

## Aspect of the reproduction project
Reproduction of the visualization stage of the empirical study,  in which a representation of the applied API categorization is generated using treemaps for better understanding of the results.

## Input data
CSV file on the project’s repo which contains a list of APIs and corresponding APIs categories: (https://github.com/gorjatschev/applying-apis/tree/main/output)


## Output data
* Treemaps with the hierarchical structure and size of abstractions
* Colorized APIs and API categories

# Finding of replication

## Process delta
How does your process differ from what’s described in the thesis or implemented in its repo? (Why?)

## Output delta

The output data is identical only different in the figure structure which it is irrelevant.
How does your output differ …? (What’s the signiffcance of any differences observed?)

# Implementation of replication

This replication use code from [this repository](https://github.com/gorjatschev/applying-apis) as a baseline. Then we remove unnecessary file that use for other part than visualization and restructure the project.

## Hardware requirements
Operating system: Linux- Ubuntu 16.04 or higher, or Windows 7 to 10, with at least 4GB RAM (8GB preferable)

## Software requirements
* Java 11 (Maven project)
* Python 3.9.6 (plotly==5.1.0, pyspark==3.1.2)
* plotly python module (5.5.0)
* pyspark python module (3.2.0)
* kaleido python module (for image export)

## Validation
Since we could not check the runtime data ( data when code is running ) with the thesis itself, we have to check it by hand by run though each of the visualization figures

Any sort of advice on how to check that the output of your process makes sense.

## Data
The input file is a analyzed data from the analyze part of the thesis which contains following data.
 > filePath, packageName, className, methodName, line, column, javaParserTypeOfElement, usedClassOfElement, isAPIClass, api, mcrCategories, mcrTags
 
While the output is the treemap visulization 

What input, output, or temporary data is assumed or produced by your process?



