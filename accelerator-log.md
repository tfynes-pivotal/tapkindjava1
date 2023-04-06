# Accelerator Log

## Options
```json
{
  "buildType" : "maven",
  "includeBuildToolWrapper" : true,
  "includeTap" : true,
  "interfaceType" : "http",
  "projectName" : "tapkindjava1"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ engine.transformations[0].validated.delegate (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, InvokeFragment, InvokeFragment, Combo, Combo, Combo, Provenance)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [src/**, func.yaml, LICENSE, NOTICE, .gitignore]
┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> included
┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/Handler.java didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/build.gradle didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/jar-assembly.xml didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Employee.java didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Person.java didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/pom.xml didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ ┃ Debug jar-assembly.xml didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/Handler.java matched [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/models/Employee.java matched [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> included
┃ ┃ ┃ ┃ ┗ Debug src/main/java/functions/models/Person.java matched [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [README.md, DEPLOYING.md]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md matched [README.md, DEPLOYING.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md, DEPLOYING.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/Handler.java didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/build.gradle didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/jar-assembly.xml didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Employee.java didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Person.java didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/pom.xml didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug jar-assembly.xml didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/Handler.java didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/models/Employee.java didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/functions/models/Person.java didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [java-function->tapkindjava1]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#buildType == 'maven' && #interfaceType == 'http') evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [pom.xml, jar-assembly.xml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/Handler.java didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/build.gradle didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/jar-assembly.xml didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Employee.java didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Person.java didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/pom.xml didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug jar-assembly.xml matched [pom.xml, jar-assembly.xml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [pom.xml, jar-assembly.xml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/Handler.java didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/models/Employee.java didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/functions/models/Person.java didn't match [pom.xml, jar-assembly.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [java-function->tapkindjava1]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#buildType == 'maven' && #interfaceType == 'cloudevents') evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#buildType == 'gradle') evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[5] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#buildType == 'gradle' && #interfaceType == 'http') evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[6] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#buildType == 'gradle' && #interfaceType == 'cloudevents') evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[7] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#interfaceType == 'cloudevents') evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[8] (InvokeFragment)
┃ ┃ ┃ ┃ ┃  Info Condition (#buildType == 'maven') evaluated to true
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[8].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[8].validated.delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[8].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[8].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#includeBuildToolWrapper) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[8].validated.delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [mvnw, mvnw.cmd, .mvn/**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/Handler.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/build.gradle didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/jar-assembly.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Employee.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Person.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug jar-assembly.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/Handler.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/models/Employee.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/models/Person.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug mvnw.cmd matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.transformations[0].sources[8].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[9] (InvokeFragment)
┃ ┃ ┃ ┃ ┃  Info Condition (#buildType == 'gradle') evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[10] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#includeTap) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[10].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, RewritePath, Combo)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[10].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [config/workload.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/Handler.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/build.gradle didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/jar-assembly.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Employee.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Person.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/pom.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug jar-assembly.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/Handler.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/models/Employee.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/functions/models/Person.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[10].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [java-function->tapkindjava1]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[10].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ Debug Path 'config/workload.yaml' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.yaml, folder=config/, filename=workload.yaml, g0=config/workload.yaml, g1=config/, g2=workload.yaml, g3=workload.yaml, g4=.yaml} and was rewritten to 'config/workload.yaml'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[10].delegate.transformations[3] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[10].delegate.transformations[3].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[10].delegate.transformations[3].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(InvokeFragment, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[10].delegate.transformations[3].delegate.transformations[0].sources[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[10].delegate.transformations[3].delegate.transformations[0].sources[0].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#bsGitRepository != null) evaluated to false
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ null ()
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[10].delegate.transformations[3].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[10].delegate.transformations[3].delegate.transformations[0].sources[1].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.transformations[0].sources[10].delegate.transformations[3].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[11] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#includeTap) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[11].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[11].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [catalog/catalog-info.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [catalog/catalog-info.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/Handler.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/build.gradle didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/jar-assembly.xml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Employee.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Person.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/pom.xml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug jar-assembly.xml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/Handler.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/models/Employee.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/functions/models/Person.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[11].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [java-function->tapkindjava1]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[12] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#includeTap) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[12].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[12].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [Tiltfile]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/Handler.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/build.gradle didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/jar-assembly.xml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Employee.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Person.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudevents/pom.xml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug jar-assembly.xml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/Handler.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/models/Employee.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/functions/models/Person.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[12].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [java-function->tapkindjava1]
┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.transformations[0].sources[13] (Provenance)
┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
