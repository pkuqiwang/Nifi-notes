# Nifi-notes

## EvaluateJsonPath
Destinate: use flowfile-attribute, this will create new attributes in the flow file
Then add new attribute map to JsonPath like 

## RouteOnAttribute
use evaluateion like the following, here category is an attribute in the incoming flowfile
${category:equals('enterprise')}
