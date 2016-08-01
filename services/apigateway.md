| Action | Description | Resource | Condition |
| --- | --- | --- | --- |
| [apigateway:GET](http://docs.aws.amazon.com/apigateway/latest/developerguide/permissions.html) | Get information about resources. | arn:aws:apigateway:$region::/restapis/*, arn:aws:apigateway:$region::/restapis/$api-id/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/methods/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/methods/$http-verb, arn:aws:apigateway:$region::/restapis/$api-id/models/*, arn:aws:apigateway:$region::/restapis/$api-id/models/$model-name, arn:aws:apigateway:$region::/restapis/$api-id/stages/*, arn:aws:apigateway:$region::/restapis/$api-id/stages/$stage-name | - |
| [apigateway:POST](http://docs.aws.amazon.com/apigateway/latest/developerguide/permissions.html) | Primarily used to create child resources.. | arn:aws:apigateway:$region::/restapis/*, arn:aws:apigateway:$region::/restapis/$api-id/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/methods/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/methods/$http-verb, arn:aws:apigateway:$region::/restapis/$api-id/models/*, arn:aws:apigateway:$region::/restapis/$api-id/models/$model-name, arn:aws:apigateway:$region::/restapis/$api-id/stages/*, arn:aws:apigateway:$region::/restapis/$api-id/stages/$stage-name | - |
| [apigateway:PUT](http://docs.aws.amazon.com/apigateway/latest/developerguide/permissions.html) | Primarily used to update resources (and, although not recommended, can be used to create child resources).. | arn:aws:apigateway:$region::/restapis/*, arn:aws:apigateway:$region::/restapis/$api-id/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/methods/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/methods/$http-verb, arn:aws:apigateway:$region::/restapis/$api-id/models/*, arn:aws:apigateway:$region::/restapis/$api-id/models/$model-name, arn:aws:apigateway:$region::/restapis/$api-id/stages/*, arn:aws:apigateway:$region::/restapis/$api-id/stages/$stage-name | - |
| [apigateway:DELETE](http://docs.aws.amazon.com/apigateway/latest/developerguide/permissions.html) | Used to delete resources. | arn:aws:apigateway:$region::/restapis/*, arn:aws:apigateway:$region::/restapis/$api-id/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/methods/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/methods/$http-verb, arn:aws:apigateway:$region::/restapis/$api-id/models/*, arn:aws:apigateway:$region::/restapis/$api-id/models/$model-name, arn:aws:apigateway:$region::/restapis/$api-id/stages/*, arn:aws:apigateway:$region::/restapis/$api-id/stages/$stage-name | - |
| [apigateway:PATCH](http://docs.aws.amazon.com/apigateway/latest/developerguide/permissions.html) | Used to update resources | arn:aws:apigateway:$region::/restapis/*, arn:aws:apigateway:$region::/restapis/$api-id/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/methods/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/methods/$http-verb, arn:aws:apigateway:$region::/restapis/$api-id/models/*, arn:aws:apigateway:$region::/restapis/$api-id/models/$model-name, arn:aws:apigateway:$region::/restapis/$api-id/stages/*, arn:aws:apigateway:$region::/restapis/$api-id/stages/$stage-name | - |
| [apigateway:HEAD](http://docs.aws.amazon.com/apigateway/latest/developerguide/permissions.html) | Same as GET but does not return the resource representation. HEAD is used primarily in testing scenarios. | arn:aws:apigateway:$region::/restapis/*, arn:aws:apigateway:$region::/restapis/$api-id/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/methods/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/methods/$http-verb, arn:aws:apigateway:$region::/restapis/$api-id/models/*, arn:aws:apigateway:$region::/restapis/$api-id/models/$model-name, arn:aws:apigateway:$region::/restapis/$api-id/stages/*, arn:aws:apigateway:$region::/restapis/$api-id/stages/$stage-name | - |
| [apigateway:OPTIONS](http://docs.aws.amazon.com/apigateway/latest/developerguide/permissions.html) | Used by callers to get information about available communication options for the target service. | arn:aws:apigateway:$region::/restapis/*, arn:aws:apigateway:$region::/restapis/$api-id/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/methods/*, arn:aws:apigateway:$region::/restapis/$api-id/resources/$resource-id/methods/$http-verb, arn:aws:apigateway:$region::/restapis/$api-id/models/*, arn:aws:apigateway:$region::/restapis/$api-id/models/$model-name, arn:aws:apigateway:$region::/restapis/$api-id/stages/*, arn:aws:apigateway:$region::/restapis/$api-id/stages/$stage-name | - |