# Hackerrank Solution Archetype

## Requirements
1. [Maven][maven] 3.6.3 or greater (for archetype usage)

## Installation
1. Clone this repository
2. Enter `hackerrank-solution-archetype` directory
3. Execute the following command:

```sh
./mvnw install
```

## Usage

1. Enter the directory you want to create a project.
2. Execute the following command:

```sh
mvn archetype:generate -B \
    -DarchetypeGroupId="com.github.marceloleite2604" \
    -DarchetypeArtifactId="hackerrank-solution-archetype" \
    -DarchetypeVersion="1.0" \
    -DgroupId="<grouṕ-id>" \
    -DartifactId="<artifact-id>" \
    -Dversion="<version>" \
    -Durl="<url>" \
    -DjavaVersion="<java-version>";
```

Where:
|Parameter    |Description                          |Example                                           |
|:------------|:------------------------------------|:-------------------------------------------------|
|group-id     | The project group ID                | `com,github.marceloleite2604.hackerrank`         |
|artifact-id  | The project artifact ID             | `hackerrank-problem-name`                        |
|version      | The project version                 | `1.0`                                            |
|url          | The project URL (optional)          | `https://github.com/MarceloLeite2604/hackerrank` |
|java-version | The project Java version (optional) | `15`                                             |

3. A new Maven project will be created inside a directory named as the `<artifact-id>` parameter.

[maven]: https://maven.apache.org/download.cgi