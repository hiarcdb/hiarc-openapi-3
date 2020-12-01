# hiarc-openapi-3
OpenAPI 3 specification for Hiarc 

```bash
openapi-generator generate -i openapi.yaml -g go -o ~/go/src/github.com/hiarcdb/hiarc-go-sdk/ -c golang-config.json
```
```bash
openapi-generator generate -i openapi.yaml -g csharp-netcore -o hiarcDotnet --additional-properties=targetFramework=netcoreapp3.1 -c csharp-config.json
```
```bash
swagger-codegen generate -i openapi.yaml -l python -o hiarc_py -c py-config.json
```
```bash
openapi-generator generate -i openapi.yaml -g java -o hiarcJava -c java-config.json
```