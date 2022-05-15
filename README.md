# device-battery-status-mock

## Config

- [.mockend.json](.mockend.json)

## REST examples

**GET**
- https://mockend.com/vctqs1/device-battery-status-mock/devices
- https://mockend.com/vctqs1/device-battery-status-mock/devices/1
- https://mockend.com/vctqs1/device-battery-status-mock/devices?baterry_order=asc
- https://mockend.com/vctqs1/device-battery-status-mock/devices?os_eq=Apple
- https://mockend.com/vctqs1/device-battery-status-mock/devices?os_eq=Apple&baterry_lt=20
- https://mockend.com/vctqs1/device-battery-status-mock/devices?limit=30&offset=1
- 
Query parameters can be used to filter, sort and paginate lists:

`_eq` `_ne` equal, not equal
`_gt`, `_gte`, `_lt`, `_lte` greater than or equal, lower than or equal contains search string
`_order=asc|desc sort` data
`limit` `offset` paginate results


POST, PUT, PATCH and DELETE requests are mocked and changes aren't saved. 

**POST**   
- https://mockend.com/vctqs1/device-battery-status-mock/devices

**PUT**    
- https://mockend.com/vctqs1/device-battery-status-mock/devices/<id>
 
**PATCH**
- https://mockend.com/vctqs1/device-battery-status-mock/devices/<id>
  
**DELETE**
- https://mockend.com/vctqs1/device-battery-status-mock/devices/<id>




## GraphQL examples

- https://mockend.com/vctqs1/device-battery-status-mock/graphql
