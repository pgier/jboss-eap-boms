JBoss Java EE 6 with Transactions
=================================

JBoss AS includes a world class transaction manager. In order to access it's full capabilites, including for example XTS, WS-AT and WS-BA, you need to use the JBossTS APIs.
 
Usage
-----

To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
                <groupId>org.jboss.bom.eap</groupId>
                <artifactId>jboss-javaee-6.0-with-transactions</artifactId>
                <version>6.2.0-build-SNAPSHOT</version>
                <type>pom</type>
                <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>

You'll need to take a look at the POM source in order to find the latest versions of plugins recommended.
