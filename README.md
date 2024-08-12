# springen
autogen spring boot controller, service, repository, entity

## install
```bash
wget https://raw.githubusercontent.com/cauta/springen/main/springen
chmod +X springen
```
springen will work at pom.xml location
## Usage
```
Options:
  -c, --controller  Create Controller
  -s, --service     Create Service
  -r, --repo        Create Repository and Entity
  -a, --all         Create Controller, Service, Repository, and Entity
  -h, --help        Display this help message
```

## Config base package
config base package in pom properties
```xml
	<properties>
		<springen.basePackage>com.example.base</springen.basePackage>
	</properties>
```

if no config from properties, springen will merge groupId and artifactId into base package
```xml
	<groupId>com.example</groupId>
	<artifactId>base</artifactId>
```
