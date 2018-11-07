
To test the archetype

	mvn clean install archetype:update-local-catalog

Then, go to another folder and run

	mvn archetype:generate -DarchetypeGroupId=net.sf.ingenias -DarchetypeCatalog=local

You should see an entry at the end

	XXXX: local -> net.sf.ingenias:iafarch (The INGENIAS Development Kit)

Choose it and perform the genration. Then go to the new folder and run the commands you want users to run
