# mvn-repo
Github hosted Maven repository

Add the following code to your pom.xml to download artifacts.

	<repositories>
    		<repository>
       			<id>lordlothar99-mvn-repo</id>
			<url>https://raw.github.com/lordlothar99/mvn-repo/master/</url>
			<snapshots>
				<enabled>true</enabled>
				<updatePolicy>always</updatePolicy>
			</snapshots>
		</repository>
	</repositories>`
