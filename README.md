To install:

```
git clone https://github.com/jbrogers63/jakartaee-starter-api jakartaee-starter-api
cd jakartaee-starter-api
mvn clean install
```

To use:

```
mvn archetype:generate \
  -DgroupId=YOUR_GROUP_ID \
  -DartifactId=YOUR_ARTIFACT_ID \
  -Dversion=YOUR_VERSION \
  -DarchetypeArtifactId=jakartaee-starter-api \
  -DarchetypeGroupId=jbrogers63 \
  -DarchetypeVersion=0.1.0 \
  -DinteractiveMode=false
```

Replace:
* YOUR_GROUP_ID with your own groupId
* YOUR_ARTIFACT_ID with your own artifactId
* YOUR_VERSION with your own version number (semantic or otherwise)
