# hiarc-openapi-3
OpenAPI 3 specification for Hiarc 

```bash
openapi-generator generate -i openapi.yaml -g go-experimental -o ~/go/src/github.com/hiarcdb/hiarc-go-sdk/
```
```bash
openapi-generator generate -i hiarc-openapi-3/openapi.yaml -g csharp-netcore -o hiarcDotnet --additional-properties=targetFramework=netcoreapp3.1 -c hiarc-openapi-3/csharp-config.json
```