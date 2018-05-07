# mule4-json-api-consumption-demo

This demonstrates calling HTTP URL to get JSON data and extract content out of nested JSON for logging purpose to answer this question - https://forums.mulesoft.com/questions/92885/extract-value-from-nested-json-object-mule-4.html

Runtime used: Mule 4.1.1

Anypoint Studio: 7.1.2



For Question - https://forums.mulesoft.com/questions/93375/dw-20-just-simply-trying-to-get-it-to-work.html

Define output payload metadata for HTTP Request object to avoid  error at `preview` time in studio - 

```
Invalid function call `Value Selector(Binary,headers)` expected
   options:
	- (lhs: Object, rhs: Name) -> Any
		- Expecting Type:
   Object, but got: Binary.
	- (lhs: Object, rhs: String) -> Any
		-
   Expecting Type: Object, but got: Binary.
	- (lhs: Array<Any>,
   rhs: Name) -> Any
		- Expecting Type: Array<Any>, but got: Binary.
	-
   (lhs: Array<Any>, rhs: String) -> Any
		- Expecting Type: Array<Any>,
   but got: Binary.
	- (lhs: Date, rhs: Name) -> Number
		- Expecting
   Type: Date, but got: Binary.
	- (lhs: DateTime, rhs: Name) ->
   Number | TimeZone
		- Expecting Type: DateTime, but got: Binary.
	-
   (lhs: LocalDateTime, rhs: Name) -> Number
		- Expecting Type:
   LocalDateTime, but got: Binary.
	- (lhs: Time, rhs: Name) ->
   Number | TimeZone
		- Expecting Type: Time, but got: Binary.
	-
   (lhs: LocalTime, rhs: Name) -> Number
		- Expecting Type: LocalTime,
   but got: Binary.
	- (lhs: Period, rhs: Name) -> Number
		- Expecting
   Type: Period, but got: Binary.
```

