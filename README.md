# Github-Activity-CLI
Java solution for the [github-user-activity](https://roadmap.sh/projects/github-user-activity) challenge from [roadmap.sh](https://roadmap.sh/).

## How to run

Open your terminal of choice and run the following commands: 

```bash
git clone https://github.com/dylancrter/GitHub-Activity-CLI.git
cd GitHub-Activity-CLI
```

If your machine isn't running Java 22, replace 22 with your version in the following pom.xml lines:

```xml
<maven.compiler.source>22</maven.compiler.source>
<maven.compiler.target>22</maven.compiler.target>
```

Run the following command to build the project

```bash
mvn clean package
```

Lastly, run this command to run the application:

```bash
java -jar target/GitHub-Activity-CLI-1.0-SNAPSHOT.jar <username> <number of actions>
```
