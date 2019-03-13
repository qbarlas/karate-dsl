# karate-dsl
Docker image for running Karate 

See https://github.com/intuit/karate to learn how to use Karate.

## Usage

### Volumes

+ `/src/features` : features folder
+ `/src/target` : output folder

### Example

```
docker run --rm -v "$PWD/tests-e2e:/src/features" -v "$PWD/reports:/src/target" qbarlas/karate-dsl
```
