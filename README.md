# carml-jar-ex
Example project for using [carml-jar](https://github.com/pmaria/carml-jar).

## System requirements

You need at leas a Java 11 JRE.

Easiest is to install it from https://adoptopenjdk.net/installation.html.

Make sure when you run `java -version` you see something like

```shell script
openjdk version "11.X.X"
```

If not you need to make sure your system `Path` environment variable is correctly pointing to your Java 11 installation.

## Executing the example

Open your favorite command line environment and navigate to this directory.

Exucute the following command.

Bash:

```shell script
java -jar carml-jar-0.0.3.jar \
  -m rml \
  -rsl input \
  -of ttl \
  -p rdfs xsd ex
```

Windows PowerShell

```shell script
java -jar carml-jar-0.0.3.jar `
  -m rml `
  -rsl input `
  -of ttl `
  -p rdfs xsd ex
```

Windows CMD

```shell script
java -jar carml-jar-0.0.3.jar ^
  -m rml ^
  -rsl input ^
  -of ttl ^
  -p rdfs xsd ex
```

## Logging
To enable DEBUG or TRACE level logging add the following to your command:

```shell script
  --spring.profiles.active=debug
```

or

```shell script
  --spring.profiles.active=trace
```
