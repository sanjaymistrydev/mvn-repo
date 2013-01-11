#mvn-repo
========

## Getting Started
Add to your pom.xml:

    <repositories>
        <repository>
            <id>tc-maven-repo</id>
            <url>https://github.com/MNicks/mvn-repo/raw/master/releases</url>
        </repository>
    </repositories>


## Recent artifacts

    <plugin>
        <groupId>com.sap.research</groupId>
        <artifactId>nwcloud-maven-plugin</artifactId>
        <version>1.0.0.RELEASE</version>
        <executions>
            <execution>
                <id>after.package</id>
                <phase>package</phase>
                <goals>
                    <goal>hint</goal>
                </goals>
            </execution>
        </executions>
    </plugin>
